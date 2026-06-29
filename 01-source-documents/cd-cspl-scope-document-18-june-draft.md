# CD_CSPL - Scope Document - 18 June - Draft.pdf

| Field | Value |
| --- | --- |
| Type | sow |
| Uploaded at | 2026-06-18T09:10:14.769556+00:00 |
| Chunks indexed | 38 |
| Artifact targets | user_story, epic, journey_map, sandbox_prototype, project_home, workshop_plan, wireframe, test_case |

## Content

_(truncated to first 50k chars - full document in `.agentic/state/`)_

```
TVS Credit 
CD/CSPL LOS - Scope 
Document 
Experience Cloud 
Salesforce Professional Services 
 
June 18 2026 

Forward-looking statements 
This presentation contains forward-looking statements about, among other things, trend analyses and statements 
regarding future events, anticipated growth and industry prospects, and our strategies, expectation or plans 
regarding product releases and enhancements. The achievement or success of the matters covered by such 
forward-looking statements involves risks, uncertainties and assumptions. If any such risks or uncertainties 
materialize or if any of the assumptions prove incorrect, results or outcomes could diﬀer materially from those 
expressed or implied by these forward-looking statements. The risks and uncertainties referred to above include 
those factors discussed in Salesforce’s reports ﬁled from time to time with the Securities and Exchange Commission, 
including, but not limited to our ability to consummate the pending acquisition of Informatica on a timely basis or at 
all; our ability to meet the expectations of our customers; uncertainties regarding Al technologies and their 
integration into our product oﬀerings; the eﬀect of evolving domestic and foreign government regulations; regulatory 
developments and regulatory investigations involving us or aﬀecting our industry; our ability to successfully introduce 
new services and product features, including related to AI and Agentforce; our ability to execute our business plans; 
the pace of change and innovation and our ability to compete in the markets in which we participate; and our ability 
to maintain and enhance our brands. 

●High Level Scope Summary 
●Proposed Scope 
●Scope Assumptions and Exclusions 
●Integration List Considered 
●MuleSoft Scope 
●Lendwise Scope 
●Other Elements of Statement Of Work (SOW) Index 

Scope - High Level Summary 
Products & Oﬀerings Channels Core Journeys Core Modules Phase 2 Items 
●Consumer 
Durables (CD) 
○Pre-approved 
(PA) 
○Non PA 
●Cross Sell Personal 
Loan (CSPL) 
●Branch 
○Direct Walkin 
customer 
●Dealers 
●Do it Yourself (DIY) 
●Marketing 
○Digital 
Marketing Lead 
(Social Media, 
SMS 
Campaigns) 
○Aggregators 
(Paisabazaar, 
TransUnion etc.) 
●New Business 
○Single 
product 
○Multi 
product 
○Parent-Child 
●Cross-sell - PL 
●Branch/Dealers/Call 
Center 
○Lead Creation 
○Loan 
Application 
●QDE 
●DDE 
●Pricing & Negotiation 
●Credit/Underwriting 
& deviations 
●Operations 
●Risk Control Unit 
(RCU) 
●Value Added 
Services (VAS) 
●Call Center 
●DIY


Conceptual Approach - Post May 12 
Phase 1: CSPL and CD 
Jun 26 - Dec 26 
Contract 
Execution 
Implementation Scope 
Foundation and CSPL - R1 
Consumer Durables - R2 Jan 27 - Mar 27 
25th  May 
2026 Jun 26     
M1Jul 26     
M2Aug 26    
M3Sep 26   
M4Oct 26  
M5Nov 26  
M6Dev 26  
M7Jan 27  
M8Feb 27  
M9Mar 27 
M10 
We are 
here
CSPL Tech Go-Live 
CD Tech Go-Live Scope Finalization (Phase 1) 
Foundation sets powers for an early CSPL go-live; CD 
launches in parallel with a small additive set; 
remaining APIs ship incrementally without blocking 
the rest of the LOS journey. 
All AI capabilities remain available per the individual 
release plan. SF+ {Removed} 
Phase 1: Scope will be contracted via SOW to initiate project - 2 Journeys CSPL & CD ONLY 
Phase 2 and Beyond: Journeys to be decided 
and separately contracted Progressive Enrichment 
TVS Credit - Day2 Support Team Warranty  Optional 
Warranty  Optional 
Warranty Optional - To be contracted additionally Implementation with 4 weeks hypercare 
Tech Go-Live 

Salesforce Professional Services   ·   May 2026 
Release Plan — CSPL & Consumer Durables 
35 
Foundation APIs 
CSPL Release 1 — early go-live Progressive Enrichment - delta APIs 42 
Incremental, post Release 2 8
CD additional APIs 
Release 2 CD - Foundation + CD speciﬁc APi’s 85 
Total APIs at full scope 
~180 endpoints across CSPL + CD 
Release 1 · Foundation + CSPL 
CSPL Early Go-Live 
The shared foundation set along with RTF setup— 
unlocks an early CSPL launch. 
    ■  Base RTF platform setup 
■  Customer onboarding: SMS/WhatsApp, EKYC 
(Aadhaar OTP), PAN, Aadhaar masking 
■  Decisioning: Multi-Bureau, BRE (Actico), Appscore, 
Fraud check (Hunter) 
■  Funding & servicing: Penny Drop, e-Mandate 
(Aadhaar), e-Sign, LMS, DMS 
■  Documents: KFS, Sanction Letter, Application, T&C, 
Form 60, OSV 
Foundational setup  lowest integration risk — 
delivers early value for TVS. Release 2 · CD Parallel Track 
Consumer Durables Launch 
A small additive set on top of the Foundation 
enables the CD product to launch in parallel with 
CSPL R2. 
■  Asset & device: SRNV / IMEIV, Asset Validation, Asset 
Dedupe, Datacultr 
■  Value-added services: extended VAS booking (One 
Assist, Epicure Shield) 
■  BRE: CD-speciﬁc rule sets layered on the shared 
engine 
■  Validate Asset Details — internal API for CD 
merchant/asset checks 
Build Incremental capabilities required for 
early launch of CD Incremental · Capability Enhancements 
Progressive Enrichment 
Delivered incrementally after Release 2 without 
holding the LOS journey 
■  Alternate KYC paths: CKYC, DigiLocker, VKYC, 
multi-vendor PAN veriﬁcation, Utility Bill Validation 
■  Alternate  Mandate breadth: Debit / Net Banking / 
UPI e-Mandates, eNACH, Open Mandate 
■  Alternate Income / Credit Veriﬁcations : Account 
Aggregator, Mobile Intelligence, Credit Health, ITR 
■  Alternate Dialer and Comms channels  : CTI/Dialer 
expansion, Email 
Remaining APIs and functionality catch up in 
waves. Priority of rollout to be prioritized 
Salesforce Professional Services 

Proposed Scope 
Our Understanding of Engagement Scope & Solution 
overview across Salesforce Clouds 

Our Understanding of Scope (1/12) 
Feature Description Scope/Solution Assumptions 
Lead Creation Lead Sourcing 
● Walk-in Customers 
● Call Center 
● Pre-approved (PA) database (CD, CSPL) 
● Saathi App 
● Lead Channels - API based Lead Creation  
○ Online (TVS Credit Website) 
○ OEMs 
○ Marketing campaigns - Social media, SMS 
○ TVS Internal Lead Management System 
○ Digital aggregator (Paisabazaar, TransUnion)                                         
● Up to fifteen (15) list views for leads created from 
channels 
● Up to ten (10) quick actions will be configured to action 
on leads 
Lead management Configure standard Out of the Box (OOTB)/Custom - 
● Lead assignment to Call Center/Field Officer 
○ Up to twenty (20) lead routing rule with up to twenty five (25) parameters. 
● Trigger geofencing check 
○  Lat/Long capture for Dealers/FOs creating loan application 
● Capture mobile number 
○ Trigger Mobile OTP validation (Mobile OTP integration) 
○ Obtain Terms & Condition/Customer Consent 
○ Capture compliance/regulatory 
● Trigger PA base check 
● Trigger ETT/NTT check 
○ Check for blocked status for ETT 
● Capture loan amount 
○ Capture asset details (in specific product cases) 
● Capture PAN/Form 60 (PAN not mandatory for amount <20k - product dependent) 
○ Form 60 - document generation (part of e-agreement) 
● Enable option for lead reassignment (Call Center/FO/Dealer) ● PA base will be setup in SF and periodically 
maintained through bulk upload option/csv file 
import/API integration. Recommendation is to have a 
bulk upload of PA base into Salesforce using SFTP 
and Mule. 
● Application will enable validations/restrictions on Form  
60 capture for existing customers. 


Our Understanding of Scope (2/12) 
Feature Description Scope/Solution Assumptions 
QDE 
Configure the following capabilities - 
● Trigger KYC check 
○ Check for OVD/ DOVD required flag from PA base (OVD/DOVD collection mandatory) 
○ Run fuzzy logic for name match (via SF Lendwise) 
■ Proceed or stop the application (based on fuzzy logic check) 
○ Name match score sent to Business Rules Engine (BRE) 
● Capture applicant personal details (Name, DOB, Gender, etc.) 
● Capture co-applicant details 
● Capture family details 
● Capture address Details (Current/Correspondence address) for OVD/DOVD cases (SF Lendwise/OCR integration) 
● Collect Officially Valid document (OVD) (for ETT - address change cases) 
○ Send link to Customer for document upload 
○ Schedule appointment (date and time) for physical document collection 
○ Create collection task/case for document collection executive. 
● Trigger geofencing check for Customer (Customer address v/s Dealer Lat/Long check) 
● Verify PAN details 
○ Trigger fuzzy logic for applicant name, DOB and Father name match (via SF Lendwise) 
● Capture live photo of Customer 
○ Watermarking of photo (use of SF Bridge App) 
○ Face match (via Face Match API integration) 
○ Face liveness check (via Face Liveness check API integration) 
○ Geo-fencing check (via Lat-long mapping API integration) 
● Trigger internal dedupe 
○ Enable native Application dedupe based on Email, Phone, PAN, Aadhar 
● Trigger dedupe (Posidex integration) 
● Trigger bureau check 
○ Trigger fuzzy logic - name match  (via SF Lendwise) 
● Trigger BRE (product specific) ● Details like personal details, addresses etc. will be pre-fetched from 
PA base/Parent Loan and displayed with option to edit. 
● For cases, where bureau/multi-bureau check has been successfully 
completed in previous 30 days, will only be trigger again in case of 
any material change like address, DOB etc. 
● Dedupe results will  be displayed via integration with Posidex(Fields 
to be displayed on screen - TBD) 
● Prepopulate customer data to avoid data entry for ETT 
● User to select manually when there are multiple dedupe results 
● Application standard dedupe rule configuration will be used. 
● Application will enable switch to Equifax Bureau based on CIBIL  
Score < 300 or on CIBIL API failure. 
Know Your Customer (KYC) 
checks 
Configure the following capabilities - 
● Enable options for initiation and completion of KYC  
○ Digital KYC 
■ CKYC (Cersai) 
■ Digilocker 
■ Biometric/Face Scan/e-KYC (through Salesforce Bridge app) 
■ Video KYC check 
○ Physical KYC (Document upload option followed by reading data through Salesforce Lendwise solution 
■ Sales user to be able to upload Documents against a defined category (Driving License (DL), Voter ID, Passport, 
Aadhaar) 
■ Option for live photo capture of KYC documents 
■ Data extraction for uploaded documents(through Salesforce Lendwise Solution) 
■ Enable option for manual data edits. 
● Configure logic for sequencing of KYC checks (CKYC → Digilocker → Biometric KYC → Physical KYC ) 
● CKYC will be mandatory for ETT’s for address change cases and  
other applicable scenarios like no previous CKYC check. 
● CKYC will be enabled for NTT Customers as well. 
● Salesforce Lendwise AI solution will be used for data extraction from 
uploaded documents. Fields will be pre-populated for successfully 
read fields - and will be editable/non editable (conditional), rest 
fields will be editable.. 
● Salesforce Bridge app will be integrated with the biometric device 
provided by Customer. Only one (1) biometric device has been 
assumed to be in scope. 
● OVD is mandatory for DOVD Customer post 90 day period (to be 
kept configurable). 
● Type of KYC checks to be configured at master level 
● Application will enable parsing of S/O or C/O in the data etched  
from KYC/Bureau specific integrations. Technical feasibility for  
complex scenarios will be determined during discovery phase.  
Manual verification will be required for such trivial cases 

Our Understanding of Scope (3/12) 
Feature Description Scope/Solution Assumptions 
DDE 
Configure the following capabilities - 
● Loan Application number generation (specific format) 
● Capture applicant employment details (including office address) 
● Capture applicant education details 
● Capture applicant self-declared income details 
● Capture family income details 
○ FOIR calculation (for loan amount < 25k - configurable in masters) - through integration 
● Capture reference details (2 references) 
● Initiate income assessment (for additional limits/loan amount requests above BRE approved amount) 
○ Send link to Customer to fetch or upload bank statement 
○ Trigger income check via (Account Aggregator, PayU, Truecaller etc.) 
○ Fuzzy logic for name check (via SF Lendwise) 
● Send details to BRE (Offer) (offer generation - basis income details,Appscore, BRE 1, employment 
details) 
● Display LTV% and max loan eligibility across different loan categories (multi-product, child loan, 
product and product sub-categories, small appliances loan) 
● Capture Offer BRE response 
○ Responses - Approve, Reject, Refer to RCU/Credit/Ops, Loan eligibility 
● Enable Product and Asset selection (based on BRE response) 
○ Single product/multi-product/small appliances (ETT) 
● Scheme and EMI option selection 
○ System will auto-populate recommended scheme (basis pre-configured rules) 
○ EMI options - Manufacture or TVS driven 
○ Scheme options - model, dealer, model + dealer, manufacturer + OEM, manufacturer + model 
(master driven) 
● Calculation of interest subvention (for OEM option) 
● Enable selection of EMI 
○ Normal EMI, Fixed EMI, Flexi EMI 
○ Calculate margin money requirement (for Fixed EMI schemes) 
● Trigger offer check (Discounts, cashback) ● Details like personal employment, education, 
self declared income etc. will be pre-fetched 
from PA base/Parent Loan and displayed with 
option to edit. 
● For cases, where bureau check has been 
successfully completed in previous 30 days, will 
only be trigger again in case of any material 
change like address, DOB etc. 
● Discounts will be applied directly to loan 
applications. Calculation will be built in SF. 
● Cashback details will be sent to LMS, applied 
post disbursement of loan. 
● Offer codes will be either applicable at Customer 
level or product level. 
● Assumption is that calculations like FOIR, 
Interest subvention, Flexi EMI are done on BRE 
and the same will be used for processing in 
Salesforce Application. 
● LMS (Loan Management System) will provide 
the required functionality/API for splitting a 
single loan application in Loan Origination 
System (LOS) into multiple LAN (Loan Account 
Numbers). This is specifically required for 
multi-product scenario (multiple assets/products 
added to a si 

Our Understanding of Scope (4/12) 
Feature Description Scope/Solution Assumptions 
DDE (cont.) 
Configure the following capabilities - 
● Enable addition of Value Added Service (VAS) 
○ Display add on from parent loan (master driven) 
■ Validation checks on VAS eligibility/applicability 
○ Option to purchase add on 
○ Add on options  (Instacard, Credit Health Report, Credit Shield, T-Health, Extend Warranty, 
Mobile Theft) 
● Calculate premium for insurance add on’s 
● Obtain Terms & Condition/Customer Consent (for each added Add On) 
● Trigger integrations for policy booking (this will be done post disbursement) 
● Set up VAS bundles (mandatory/non mandatory VAS) 
○ Price calculation 
● Option to add multi-product 
○ Eligibility check (basis BRE response) 
● Check for valid open mandate for ETT (if opting for same bank account) 
● Single mandate 
● Single disbursement 
● Option to add additional products under parent product (parent-child scenario) 
● Enable tagging of multi-products and child products 
● Enable option for asset changes in loan application 
● Trigger BRE run 
○ Final list of approved products 
● Calculation of final approved amount 
○ LTV calculation 
○ Minimum of LTV and  approved from CRO/BRE 
● Calculate Net Funded amount (based on formula) 
● Calculate Maximum Finance amount (based on formula) 
○ Max finance amount validation 
● Generate loan summary details 
● Calculate Broken Period Interest (BPI) (based on formula) 
● Calculate Processing Fees (PF) / Other charges 
● Refer to Operations/RCU/Credit/FO (based on BRE response) 
● Trigger PA Base update (limit update post disbursement confirmation) ● Displayed VAS options will be master driven 
dependent on parameters like dealer, OEM, 
State, PINCODE, Branch, Product/Portfolio. 
● Both in multi-product and parent-child product 
scenarios, the application will be split before 
sending details to LMS for separate LAN 
creations. 
● Up to five (5) levels of approval hierarchy will be 
setup as part of approval process. 
● Premium calculation for Add Ons will be part of 
SF Application. Calculation will be restricted to 
basic formulae based on fields from masters. 


Our Understanding of Scope (5/12) 
Feature Description Scope/Solution Assumptions 
Pricing & Negotiation 
Configure the following capabilities - 
● Option to edit Rate of Interest (ROI) 
● Option to edit Processing Fees (PF) 
● Trigger deviation check 
○ Deviations approval 
● Generate Sanction letter 
○ Multiple sanction letters (multi-product) 
○ Single sanction letter (multiple small appliances) 
● Enable option to cancel loan application (if Customer does not want to proceed) 
● Capture banking details 
○ Pre-fetch bank account details from PA base for ETT 
○ Check for valid open mandate for ETT (if opting for same bank account) 
○ Fuzzy logic to match names (via SF Lendwise) 
● Trigger banking dedupe check (if more than 2 mandates exist on same account) 
● Set up mandate setup 
○ E-mandate (net-banking, UPI Id, debit card, Aadhaar) 
○ Physical mandate 
■ Capture image 
● Set image resolution (through ACH resolution API) 
● Trigger BRE run (Pre-disbursal) 
● Generate E-sign Agreement 
○ Send link to Customer (SMS, Whatsapp, Email) 
● Trigger Dealer geofencing check 
● Email ID verification 
● IMEI/Serial Number validation (for mobile assets) - (available only for dealers) 
○ Trigger IMEI dedupe check (through OEM integration) 
● Trigger Asset locking for mobile devices (through integration) 
○ Option to rollback locking (through integration) 
● Enable upload of invoice (for Dealers) 
○ LFR/RR (invoice pull API) 
○ Manual upload followed by OCR (send to Loan Management System (LMS)) 
● Auto population of data based on invoice read 
● Promoter selection 
● Generate Pre- 
● Generate Pre Delivery Order/Delivery Order (DO) (through integration) ● ROI and PF change is only applicable for 
CSPL product. 
● Application Form, Form 60 if opted, 
Agreement including the Schedule of 
Charges and Repayment Schedule, KFS will 
be part of e-agreement. 
● Up to ten (10) OEM’s have been considered  
for IMEI dedupe check integrations 
Down Payment ● Generate Bitly link to payment page 
● Send payment page link via Email/SMS/WhatsApp  
● Initiate capture payment(incl QR Code generation) via integration with Payment Gateway 
● Generate receipt 
● Ability to track payment status 

Our Understanding of Scope (6/12) 
Feature Description Scope/Solution Assumptions 
Credit Configure the following capabilities - 
● Option to pick application from queue 
● Review loan application 
○ Credit Analysis Memorandum (CAM) 
○ BRE responses (BRE0, 1, 2, 3, 4) 
○ Bureau responses 
○ PA Base 
● Option to send back loan application to Dealer 
● Option to refer loan application to Operations 
● Option for bulk upload of cases (stuck cases) 
● Decision loan application 
○ Approve/Reject cases with comments 
● Trigger approval workflow 
● Enable approval at 
● Option to reopen rejected cases ● Up to two (2) format of CAM, one 
each for CD and CSPL. Minor 
variations in sections based on 
multi products will be 
accommodates within the primary 
CAM format. 
● Approval matrix will be configured in 
SF as per the requirement. 
Operations Configure the following capabilities - 
● Option to pick application from queue/Enable FIFO based allocation 
● Review loan application 
● Trigger bank account check 
○ Capture integration responses (Penny Drop/Penny Less) 
● Option to send back loan application to Dealer/CC/SCE - based on CD/CSPL journey 
● Option to send loan application to Credit 
● Decision loan application 
○ Approve/Reject/Hold cases with comments 
● Delivery Order generation 
○ DO verification (NSTP) 
● Trigger disbursement (LMS integration) 
● Push Invoice and Delivery Order documents to LMS (LMS integration) 
● Send loan application details to CERSA I and Data Mart 
● Enable reverse update in Application for cancelled loans (data feed from LMS for cancelled loans) 

Our Understanding of Scope (7/12) 
Feature Description Scope/Solution Assumptions 
Call Center (Channel) Configure the following capabilities - 
● Computer Telephony Integration (CTI) integration with up to three (3) customer provided CTI adaptor 
● Enable routing of PA offers and digital leads to Call Center 
○ Routing logic for ETT 
○ Routing logic for NTT 
● Enable outbound calling (CTI integration) 
○ Pre-populate Customer/Lead/Application data 
● Option to initiate KYC checks 
● Address confirmation 
● Application number generation 
● Capture branch code of dealer (nearest to correspondence address location) 
● Option to capture Income details and initiate income assessment 
● Trigger BRE run 
● Asset selection 
● Display list and address of dealer based on product selection 
● Option to assign FO basis dealer selection 
○ Assignment to FO/Dealer 
● Handle loan application escalation ● CTI vendor should have a connector 
to Salesforce. Building a connector is 
out of scope for SFDC. 
Document Collection 
Executive (DCE) Configure the following capabilities - 
● Assignment to DCE (internal/external) 
○ Assignment logic basis PINCODE (DCE PINCODE and Customer PINCODE) 
● Send Customer details to DCE 
● Upload Customer documents 
● Watermarking of uploaded documents (live image capture - gallery restriction) 
○ Trigger fuzzy logic check 
● Trigger geofencing check 
○ Option to re-assign application ● For DCE document collection cases, 
Customer will receive SMS with DCE 
details and document collection 
appointment date and time. 

Our Understanding of Scope (8/12) 
Feature Description Scope/Solution Assumptions 
DIY Journey (CD/CSPL) Configure the following capabilities - 
● Customer clicks on PA offer. 
○ Enable login (authentication using mobile number or PAN number) 
● Enable KYC check (CKYC/ Digilocker,/KYC document upload) 
● Proceed with address confirmation (permanent/communication) 
● Capture branch code of dealer nearest to Correspondence address location (auto populated) 
● Generate Loan application number 
● Capture income details 
○ Proceed with Income assessment (for higher limit) 
● Capture Bank details 
● Trigger BRE run 
● Display Offer - Loan and Add on details (Offers page) 
● Display loan summary (based on offer selection) 
● Selection of asset (applicable for CD) 
● Display list and address of Dealer based on product selection. (applicable for CD) 
● FO assignment basis dealer selection (applicable for CD) 
● Capture Live photo 
● Mandate setup (E-mandate, Physical mandate) 
● E-agreement 
● Request for disbursement (CSPL only) 
● Enable option to resume journey (based on previous login history and stage) 
● DIY journey will be initiated from TVS 
Credit Website, Saathi App, Link sent 
to Customer via SMS, Whatsapp 
● SFDC does not recommend using a 
pre-authenticated Link/URLfor DIY 
journey. 
● All KYC options applicable on the 
primary non DIY journey except 
eKYC/Biometric will be available to 
Customer on DIY journey. 


Our Understanding of Scope (9/12) 
Feature Description Scope/Solution Assumptions 
RCU (Parallel Process) 
Configure the following capabilities - 
● Option to pick application from queue 
● RCU Initiation and allocation flow include applicants, co-applicants etc 
● STP/NSTP queue (basis BRE run) 
● Review loan application 
○ Lead, QDE, DDE, Pricing and Nego, BRE run, Uploaded documents 
● Mark items requiring review 
● Send back to CC/SCE/Dealer/FO 
● Send back to Pricing/Negotiation (bank details name mismatch) 
● Decision loan application 
○ Approve/Reject/Hold cases with comments 
● Capture final RCU decision (RCU manager) 
Stage Gate Validation ● Ability to validate of stage gates before moving to next stage. 
Loan Account Setup ● Create Customer Account via integration with Core Banking System (CBS) 
● Create Loan Account via integration with Loan Management System (LMS) ● Orchestration for Customer account creation and LAN creation 
will be done through Mule. 
● LAN number will be generated in Salesforce and sent to LMS. 
Stage Reversal 
Configure the following capabilities - 
● Enable stage reversal to re-process the application at the following stages 
○ Credit to Dealer/FO 
○ Ops to Credit 
○ Ops to Dealer/FO 
Query ● Ability to assign the query to a user 
● Ability to respond to query 
Turn Around Time (TAT) 
calculations ● Calculate TAT of the application 
● TAT Report ● TAT will be calculated only at the 
loan stage levels 
● Query/s TAT to be deducted from the 
loan stage TAT and to be counted 
under the Query owner's individual TAT 

Our Understanding of Scope (10/12) 
Feature Description Scope/Solution Assumptions 
Documents 
Checklist & 
Approval ● Configure Document Types and Document Checklist 
● Document Approval Process ● Up to ten (10) checklists and thirty (30) documents will be configured for 
document checklist 
Document 
Generation ● Generation of documents (e.g. Application Form, Sanction Letter, KFS, 
Repayment Schedule, Welcome Letter (After disbursement), Delivery Order, 
Loan agreement) ● Salesforce Application will call Customer document generation service (API__ 
for generation of required documents at specific stages of loan journey. 
Notification Configure standard OOTB - 
● Configure Email, SMS and Whatsapp templates for notifications ● Up to ten (10) Email, ten (10) SMS and ten (10) Whatsapp notification 
templates will be configured for internal and external communication. 
● SFDC will integrate with Customer existing Email, SMS and Whatsapp services 
provider for sending notifications. 
● Communication through Email, Whatsapp and SMS are only for outbound 
messaging. No inbound communication is considered in scope for this 
engagement. 
Reports and 
Dashboards Configure standard OOTB - 
● Reports and Dashboards. ● Up to twenty five (25) reports and ten (10) dashboards are included in scope of 
this implementation.. 
● Reports UI is non customizable and standard formats will be used. 
● Export of reports will be limited to standard functionality and pushing report to 
any external repository/system is out of scope 
● Dashboard UI is non customizable 
Master Data 
Import ● Set up master data tables in Salesforce Application. 
● Salesforce to provide templates for data import. Customer will extract, cleans 
and transform the data and provide data to SFDC in CSV format for data load. 
List of masters could include - 
○ Product Master 
○ Scheme Master 
○ Terms and Conditions Master 
○ Deviations Master 
○ Fee and Charges Master 
○ User Master 
○ Branch Master 
○ Dealer Master 
● Configure Manufacturing Processing Fees (MPF) calculation for Scheme  
Master 
○ Up to two (2) fields will be calculated on Scheme Master. ● Up to forty (40) masters objects are included in scope of this implementation.. 
● Up to one (1) time setup and load of masters (Note: Upload will be done 
manually using Salesforce Data Loader tool). SFDC will carry out one (1) data 
load in UAT and one (1) data load in production environment of SF Application. 
● Up to one (1) custom screen will be provided to OEM users (TVS internal  
users) to to map/demap schemes/dealers. 
● Technical  feasibility of MPF calculation will be determined and finalized during  
the discovery phase. 
● Cleansing, deduplication and transformation of master data for migration needs 
be carried out at source by the Customer. 
● Maker-checker process for up to thirty (30) masters is included in the current 
scope of implementation. 
● Regular sync of Master between source system and Application is out of 
current scope for SFDC. 
● TVS Credit Master Maintenance team will be responsible for adding, removing, 
updating masters in the application. 

Our Understanding of Scope (11/12) 
Capability Feature Description Scope/Solution Assumptions 
Mobile Apps Salesforce 
standard mobile 
App● Configure standard Salesforce mobile app ● No offline functionality will be supported on 
SF standard mobile app. 
Salesforce 
Bridge App ● Bridge App (React Native)  for iOS and Android with Mobile and Tablet Support 
○ Salesforce SDK based Authentication 
○ Biometric KYC device integration (to enable biometric based Aadhaar e-kyc 
authentication) 
■ Capture of PID and Salesforce Server Integration 
○ Document Capture 
■ Transformation (Crop / Rotate, Brightness etc) 
■ Watermarking (Lat Long , Date Time) 
■ Size Limit 
■ Gallery upload/download Restriction ● No oﬄine functionality will be supported 
on SF Bridge app. 
● Up to one (1) Customer provided 
biometric device will be integrated with 
SF bridge app for enabling KYC. 
Salesforce 
Mobile Publisher 
(External Users) ● Conﬁgure Salesforce Mobile Publisher App 

Technical scope (12/12) 
Service Area Description Scope/Solution Assumptions 
Environment 
setup Setup of the Salesforce instance including sandbox creation and one (1) Production 
Instance as mentioned below 
● One Dev Sandbox for development and One additional Dev Sandbox for 
Support 
● One Testing Sandbox 
● One UAT Sandbox ( Full Copy ) 
● One Performance Testing Sandbox ( Full Copy / Scale Test Sandbox) 
● One Production instance 
User 
Management ● Gather requirements from different teams to arrive at security and visibility 
rules to design the final role hierarchy. 
● Create up to twelve (12) profiles and twenty (20) permission sets 
● Create up to thirty (30) roles. Role hierarchy will be created and maintained 
manually. 
● Create up to twenty five (25) Sharing rules and Organisation Wide Default 
rules ● Role hierarchy set up in the Application differs from the 
organization role hierarchy. 
● User permissions will be defined by roles and profiles 
● Classes, pages, access will be controlled at profile level 
● Record access is at hierarchy level and based on sharing rules. 
● Concurrent sessions will be enabled at profile level only. During 
the define phase, the number of parallel sessions which needs 
to be allowed will be established. 
Objects setup Standard objects setup and relationships to support customer service functions: 
● Application Form 
● Applicant 
● Application Form Product 
● Case 
● Contact 
● Activities, Tasks, Events 
Up to fifty (50) custom objects will be setup with up to fifty (50) fields each 
Audit Tracking SFDC will enable standard out of the box 
● Configuration of Audit Tracking for up to hundred (100) fields on any given 
object ● Standard History Tracking UI will be used for the 
implementation. 

Core Implementation Assumptions 
Functional Scope 
● A total of one hundred and ninety (190) system endpoints across eighty five (85) systems 
are included in scope of this implementation. Any additional integration touch-points to be 
included in scope will have commercial and implementation timeline impact. 
● Customer will share the final list of integration touch-points and system details prior to 
commencement of discovery/define phase of the project. . 
● Finalized business process flows signed off by Customer should be available before 
commencement of design phase for each line of business. Business process flows must 
have detailed process explanations and detailed validations for all happy and failure 
paths. 
● Business requirements will have detailed fields to be captured at each screen and 
validations at screen and field level. 
 
Testing 
● Regression testing will be owned and performed by TVS credit with support from SFDC 
● Salesforce testing will be limited to Google Chrome browser and devices (Mobile - iOS, 
Android - make to be confirmed during development phase, Desktop - Mac) 
● Android device needs to be provided by TVS Credit for testing. Only one (1) device 
model will be tested. 
● User Acceptance Testing (UAT) will be conducted by Customer. The development of a 
test plan document and test cases will be the responsibility of the Customer 
● SFDC will own and support System Integration Testing (SIT). SFDC will provide the list of 
test cases executed during functional testing along with pass percentage, screenshots 
wherever applicable. 
Middleware 
● Any encryption of payload (using Symmetric or Asymmetric 
algorithms) will be handed in MuleSoft. 
● All data parsing requirements w.r.t integrations will be handled on 
MuleSoft. 
Bulk Upload Features 
● Application will not support any data uploads using excel files, any 
data upload should be using pre-defined CSV  files using the 
Application standard import wizard 
● Data load will be done through the standard import wizard. UI of 
import wizard is not customizable and should be  used as is. 
Other 
● Salesforce Bridge App will be used to support features like file 
compression, image transformation, document watermarking, 
document merging during document upload using Bridge mobile app. 
● Scanning the file during upload etc. is out of scope and file security 
will only be limited to validating the file extensions. 
● Document preview feature in SF Application will be restricted to only 
certain types of documents. TIFF images are not supported. 
Travel and Expenses (T&E) 
● Any Travel related expenses will be billed on actuals. Email approvals 
will be sought before travel. 
● Separate Invoice with supporting documents will be provided for T&E 
invoice payments. 


Core Implementation Assumptions 
Additional Assumptions 
● Application will display pass/fail status of the outbound APIs but not inbound APIs If the 
API fails, display pre-configured error message (and not technical error) 
● Application will support multiple dealer onboarding with the same mobile number 
provided the unique identity is maintained with a combination of mobile number and 
additional field (e.g. unique email id). 
● Application will enable KYC and Repayment mandate modes based on the Dealer Risk 
category (derived from Masters) 
● Customer will share the final list of integration touch-points and system details prior to 
commencement of discovery/define phase of the project. . 
● Finalized business process flows signed off by Customer should be available before 
commencement of design phase for each line of business. Business process flows must 
have detailed process explanations and detailed validations for all happy and failure 
paths. 
● Business requirements will have detailed fields to be captured at each screen and 
validations at screen and field level. 
 
Testing 
● Regression testing will be owned and performed by TVS credit with support from SFDC 
● Salesforce testing will be limited to Google Chrome browser and devices (Mobile - iOS, 
Android - make to be confirmed during development phase, Desktop - Mac) 
● Android device needs to be provided by TVS Credit for testing. Only one (1) device 
model will be tested. 
● User Acceptance Testing (UAT) will be conducted by Customer. The development of a 
test plan document and test cases will be the responsibility of the Customer 
● SFDC will own and support System Integration Testing (SIT). SFDC will provide the list of 
test cases executed during functional testing along with pass percentage, screenshots 
wherever applicable. 
Middleware 
● Any encryption of payload (using Symmetric or Asymmetric 
algorithms) will be handed in MuleSoft. 
● All data parsing requirements w.r.t integrations will be handled on 
MuleSoft. 
Bulk Upload Features 
● Application will not support any data uploads using excel files, any 
data upload should be using pre-defined CSV  files using the 
Application standard import wizard 
● Data load will be done through the standard import wizard. UI of 
import wizard is not customizable and should be  used as is. 
Other 
● Salesforce Bridge App will be used to support features like file 
compression, image transformation, document watermarking, 
document merging during document upload using Bridge mobile app. 
● Scanning the file during upload etc. is out of scope and file security 
will only be limited to validating the file extensions. 
● Document preview feature in SF Application will be restricted to only 
certain types of documents. TIFF images are not supported. 
Travel and Expenses (T&E) 
● Any Travel related expenses will be billed on actuals. Email approvals 
will be sought before travel. 
● Separate Invoice with supporting documents will be provided for T&E 
invoice payments. 


Scope Exclusions 
● Any offline capabilities on any mobile app. 
● Fully Custom mobile app based on Salesforce SDK except for Bridge App 
included in scope for biometric KYC and document transformation. 
● Mobile app for external users (Mobile Publisher or Custom app). 
● Any ETL development for master data loads in current scope of work. 
● Any development on Customer Community for Self Help portals and 
customer self servicing in current scope of work. 
● BRE related requirements except for basic formulas and calculations, which  
can be supported on SFDC Platform Out of the Box. 
● Loan Management System features and functionalities, specifically Loan  
Servicing, Pre-EMI, Repayment Schedule Variations, Payment Requisition  
and any other Disbursement activities are not included in scope. 
● Document Management System (DMS) related workflows and  
functionalities. 
● Collections process and related functionalities 
● Advanced Analytical reports requiring separate licenses. 
● Data archival and setup including but not limited to data archival, viewing of  
archived data from Customer legacy systems in current scope of work. 
● Any requirement requiring reading and parsing offline Aadhaar XML. 
● API development or testing of API’s on Customer systems. 
● Any reporting on data not residing in Application. Any analytical reporting  
involving significant calculations or external data like LMS data is out of  
scope. 
● Any marketing or campaign related functionalities 
● Internal Rate of Return ( IRR) calculator 
● Incentive calculator 
● Automation test scripts development and Automation Testing 
● Performance, security, scale and load testing. SFDC will support 
Customer in triaging and addressing issues arising out of these testing 
wherever technical feasible. 
● DevOps set up and implementation. 
● Training of end users. 
● Change management - Customer will conduct all Change Management 
activities, including but not limited to: 
 stakeholder identification; 
 end user training and preparation of any training materials (eg: 
manuals, deck) for end users; 
 end user communications; and 
 adoption planning and execution. 


Scope considered post go-live of phase 1 
1.Routing logic/ Segmentation 
2.Archival 
3.Service Cloud Voice - Setup and Conﬁguration 
4.Elements of Scope Considered as Phase 2 

Here are elements which can be considered by TVS as subsequent 
Improvements / enhancements and need not be part of initial journey scope 
Input what we captured in common response sheet - Out of Scope Out of Scope - Not Considered 

To be updated finally 
●Total Systems: 85     
●Total System Endpoints: 190   
●Release 1 (CSPL R1): 35 New    
●Release 2 (CD): 8 New    
●Release 3 (CSPL R2): 42 New     Integration List Considered 

Indicative List of Integrations  (1 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CD CSPL R2 
Lat Long conversion Google Sync New Reuse Reuse 
MapMyIndia Sync New
SMS API (OTP included) Airtel Async New Reuse Reuse 
Karix Async New
WhatsApp Gupshup Async New Reuse Reuse 
Email Service TVSCS Internal API (SMTP) Sync New
Email Validation Perfios API(Karza) Sync New Reuse Reuse 
PA base TVSCS Internal API Sync New Reuse Reuse 
PA Limit TVSCS Internal API Sync New Reuse Reuse 
CKYC Trackwizz Async New

Indicative List of Integrations  (2 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CD CSPL R2 
Digilocker Digio Async New
Equal Sync New
VKYC Karza ASync New
Hyperverge ASync New
Digio ASync New
IDFY ASync New
EKYC(Aadhaar OTP) Protean ASync New Reuse Reuse 
Perfios ASync New
PAN Validation Equals Sync New Reuse Reuse 
Karza Sync New
NSDL Sync New
PAN Pro / Advance PAN validation Digitap Sync New
Bureau ID Sync New
PAN tampering IDFY Sync Supported through Lendwise 
Fuzzy Logic API -Names TVSCS Internal API Sync Supported through Lendwise 

Indicative List of Integrations  (3 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CDç CSPL R2 
Penny Drop or Penny Less (not both per 
vendor) Kotak ASync New Reuse Reuse 
Paynimo ASync New
Timble ASync New
Equals ASync New
Axis ASync New
Dedupe Posidex (TVSCS Wrapper API) Sync New Reuse Reuse 
Utility bill validations Signzy Sync New
Karza Sync New
HyperVerge Sync New
Multi-Bureau CIBIL ASync New Reuse Reuse 
Equifax ASync New
CRIF ASync New
Face Liveness API IDFY Sync New Reuse Reuse 
TVSCS Internal API (DAM API) Sync New

Indicative List of Integrations  (4 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CDç CSPL R2 
Watermarking TVSCS Internal API Sync Supported through SF Bridge App 
ID Proof OCR IDFY Sync Supported through Lendwise 
Digio Sync Supported through Lendwise 
TVSCS Internal API Sync Supported through Lendwise 
Address Proof OCR IDFY Sync Supported through Lendwise 
Digio Sync Supported through Lendwise 
TVSCS Internal API Sync Supported through Lendwise 
Aadhar Masking IDFY Sync New Reuse Reuse 
Digio Sync New
TVSCS Internal API Sync New
Face Match IDFY Sync New Reuse Reuse 
Digio Sync New
TVSCS Internal API Sync New

Indicative List of Integrations  (5 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CDç CSPL R2 
E Mandate (Aadhaar) TVSCS Wrapper API Sync New Reuse Reuse 
E Mandate (Debit) TVSCS Wrapper API Sync New
E Mandate (Net banking) TVSCS Wrapper API Sync New
E mandate (UPI) TVSCS Wrapper API Sync New
Open Mandate UNCIA Sync New
eNACH TBD Sync New
BRE Actico Sync & Async New New Reuse 
Biometric/Face Biometric Protean Sync New Reuse Reuse 
Document generation - KFS TVSCS Internal API (TVS Gaslite) Sync New Reuse Reuse 
Document generation - Sanction Letter TVSCS Internal API (TVS Gaslite) Sync New Reuse Reuse 
Document generation - Application 
Agreement TVSCS Internal API (TVS Gaslite) Sync New Reuse Reuse 
Document generation - T&C TVSCS Internal API (TVS Gaslite) Sync New Reuse Reuse 
Document generation - Insurance Form TVSCS Internal API (TVS Gaslite) Sync New Reuse Reuse 

Indicative List of Integrations  (6 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CD CSPL R2 
Document generation - Form 60 TVSCS Internal API (TVS Gaslite) Sync New Reuse Reuse 
Document generation - OSV TVSCS Internal API (TVS Gaslite) Sync New Reuse Reuse 
Document Storage (DMS) TVSCS Internal API Async New Reuse Reuse 
LMS - Repayment Schedule API AAYU API - EBIX Sync New
UNCIA Sync New Reuse Reuse 
LMS - Disbursement TVSCS Internal API Async New
UNCIA Async New Reuse Reuse 
LMS - LAN/Account Opening Internal API Async New
UNCIA Async New Reuse Reuse 
Appscore/Scorecard TVSCS Internal API ASync New Reuse Reuse 
SRNV/IMEIV OEM wise integration Sync New 
URL shortening TVS internal API Sync New Reuse Reuse 

Indicative List of Integrations  (7 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CD CSPL R2 
Mobile Intelligence API Pay U Sync New
Truecaller Sync New
Account Aggregator Perfios ASync New Reuse Reuse 
OneMoney Sync New
VAS booking API Galaxy Sync New Reuse Reuse 
T-health Sync New
One assist Sync New 
Epicure shield Sync New 
Bank Statement Analyzer (BSA) - PDF 
upload, Net Banking, Scan document Perfios ASync New Reuse Reuse 
E-Sign API Leegality ASync New Reuse Reuse 

Indicative List of Integrations  (8 of 8 ) 
Functionality/System API/Vendors Pattern Foundation (CSPL R1) CD CSPL R2 
Fraud check Experian API (Hunter) ASync New Reuse Reuse 
Datacultr app confirmation Datacultr Sync New 
Validate Asset Details TVSCS Internal API Sync New 
CTI (Dialers) Ameyo Sync New Reuse Reuse 
Ebix Sync New
Enser (Taurus is being sunset) Sync New
Lead Management System (Lead API) TVSCS Internal API (TBD) Sync New Reuse Reuse 
ITR Form 27A TBD Sync New
Asset Validation TVSCS Internal API Sync New 
Asset Dedupe TVSCS Internal API (TBD) Sync New 
Credit Health Report TBD Sync New
SIEM integration Requested via email by Vignesh - Keith to note  

MuleSo Scope 

MuleSo - Scope of Work 
MuleSoft Focus Area Scope Description Key Assumptions & Dependencies 
MuleSoft Platform Review/Setup ●Integration Platform discovery based on TVS enterprise and 
Infrastructure guidelines and create the  MuleSoft Platform 
architecture document 
●MuleSoft Platform setup 
○ MuleSoft managed control plane on  MuleSoft Cloud 
○ MuleSoft RTF deployed on customer hosted Kubernetes (K8) 
infrastructure (on-prem or AWS) consisting of 2 MuleSoft RTF 
cluster Prod and Non Prod on Customer 
○ MuleSoft RTF Non-Prod Cluster will host DEV, TEST/SIT, UAT, 
Preprod/Perf Test; Prod will host PROD environment 
●Setup  the Persistence Gateway,  setup and implement 
improvement as required. 
●Support the customer in setup secure connectivity to their AWS 
landing zone and data center via Private spaces, VPN, VPC  
conﬁgurations 
●Setup of Business groups, Teams, Connected Apps, SSO 
●Alerts, Notiﬁcations and Anypoint Monitoring setup ●MuleSoft license purchase and org enablement should have be 
completed before the start of the project. 
●Secure network access to customer cloud landing zone, 
on-premises data centers and 3rd party service providers will be 
provided by the customer 
●MuleSoft RTF Clusters and runtime servers(pods)  will get installed 
inside the customer’s landing zone on Kubernetes Cluster 
conﬁgured by the Customer. Infrastructure will be owned & 
provisioned by customer, including AWS landing zone 
conﬁguration, creation/deployment and conﬁguration of  
chef/ansible/terraform scripts, and the Postgres DB required for 
the Persistence Gateway. 
●Anypoint Monitoring will be used to monitor the MuleSoft 
platform, limited to the speciﬁc features and user tiers selected in 
the customer's subscription. If there are requirements to forward 
logs external log monitoring tool, the same will be provisioned and 
conﬁgured by the Customer 
MuleSoft implementation - CSPL R1 ●Implementation of MuleSoft ﬂows/endpoints; 
○ Connection to 35 internal systems or 3rd party services 
resulting in approximately 80 MuleSoft ﬂows or endpoints 
○ 12 orchestrated MuleSoft ﬂows related to the CSPL Journey 
○ 1 API proxy to secure API calls from SFDC 
○ 9 MuleSoft batch ﬂows for incremental update of master data 
○ The complexity distribution considered is 54% Low, 40% 
Medium, 6% High 
●Test Support during  UAT,  Go-Live and Post Go-Live hypercare 
period ●APIs will be implemented using  API led Connectivity  approach and 
following “ Domain driven Design ”
●Change  to customer’s applications  to enable integrations will be 
done by the customer team 
●Customer is responsible for providing the right logic to identify delta 
records for incremental Batch Process. 
●Batch size for Mulesoft batch flows are 10000 rows or 100KB size per 
run.

MuleSo - Scope of Work 
MuleSoft Focus Area Scope Description Key Assumptions & Dependencies 
MuleSoft implementation - CD R1 ●Implementation of MuleSoft ﬂows/endpoints; 
○ Connection to 8 additional internal systems or 3rd party 
services resulting in approximately 17 MuleSoft ﬂows or 
endpoints 
○ 10 orchestrated MuleSoft ﬂows related to the CD Journey 
○ Updates to 1 API proxy to secure API calls from SFDC 
○ 9 MuleSoft batch ﬂows for incremental update of master data 
○ The complexity distribution considered is 45% Low, 50% 
Medium, 15% High 
●Test Support during  UAT,  Go-Live and Post Go-Live hypercare 
period ●APIs will be implemented using  API led Connectivity  approach and 
following “ Domain driven Design ”
●Change  to customer’s applications  to enable integrations will be 
done by the customer team 
●Customer is responsible for providing the right logic to identify delta 
records for incremental Batch Process. 
●Batch size for Mulesoft batch flows are 10000 rows or 100KB size per 
run.
MuleSoft implementation - CSPL & 
CD R2 ●Implementation of MuleSoft ﬂows/endpoints; 
○ Connection to 42 additional internal systems or 3rd party 
services, system level orchestrated ﬂows resulting in 
approximately 95 MuleSoft ﬂows or endpoints 
○ Updates to the 20  orchestrated MuleSoft ﬂows related to the 
CSPL and CD Journey 
○ The complexity distribution considered is 75% Low, 25% 
Medium, 0% High 
●Test Support during  UAT,  Go-Live and Post Go-Live hypercare 
period ●APIs will be implemented using  API led Connectivity  approach and 
following “ Domain driven Design ”
●Change  to customer’s applications  to enable integrations will be 
done by the customer team 
●Customer is responsible for providing the right logic to identify delta 
records for incremental Batch Process. 

MuleSo - Assumptions 
Key assumptions have been made in the development of our proposal. We will need to re-estimate or raise a change order if there are any changes to 
these assumptions. These assumptions include but not limited to following 
●The effort and cost estimates are based on the documented integration use cases and assumptions derived from our experience regarding the 
required MuleSoft flows. During Detailed Discovery, these use cases and complexity assumptions will be verified. Any material change to the 
integrated use cases or their complexity will be subject to the Change Control process. 
●Effort estimates will be revised if detailed discovery suggests transitioning scheduled jobs to event-driven, near-real-time integrations, contingent 
upon the application's event generation capability. 
●Data synchronization with the Enterprise Data Warehouse (EDW) is excluded from the MuleSoft scope. It is recommended to utilize native EDW 
connectors
```

---
_Auto-generated from in-app state. Source field: `documents['CD_CSPL - Scope Document - 18 June - Draft.pdf']`. Last updated: 2026-06-29T10:11:44.678915+00:00._
