# ENHANCED ACCESS PROGRAM (EAP)
South Bay Primary Care Management Group (SBPCM) Repository - Mobile App

Background:

EAP is a distinguishing Telemedicine platform unique to South Bay Primary Care Group initially developed nearly 10 years ago, allowing Telemedicine visits.
The platform has been developed in Ruby, using the Ruby-on-Rails platform.The back-end hosting providers are understood to be Google Cloud instances, not under the ownership of SBPCG.
As EAP exists currently, demonstrated access is through (from a Patient Perspective) 
  Through existing log-in to the Website Portal, requiring email verification
  Through mobile phone, using text verification, after access being granted to native use to the mobile device;
  Additional 2-factor Identifaction

Objective:

Create a native iOS App, approved by Apple, allowing Patients to download the App, bypass aformentioned parameters, and join a Telemedicine session through Biometric (FaceID) authentication;
Create a native Android App, approved by Google, allowing Patients to download the App, bypass aformentioned parameters, and join a Telemedicine session through Biometric (FaceID) authentication;

Develop a front-end (iOS/Android) interfaces for Patient access
Establish a dedicated back-end server to enable capture of length of visit;
Capture this data, sending it as encryaed metadata to existing Patient history  

ISSUES/CHALLENGES:;

The existing EAP application layers are understood to be on Google Cloud instance(s) not under the owenership or control of SBPMG;
  It isn't understood if the existing server(s) are using the Shareed Hosting, or Dedicated Virtual Machine plan;
The Rails code needs to be migrated to [recommended] a dedicated Virtual Machine under full-ownership of SBPMG

Action Items:

Migrate existing code-base, in conjunction with the initial Developer's assistence (giving him full Administrative Access) to SBPMG's server;
Develop a seperate instance to manage data transmitted from the new EAP iOS and Adroid App, to a new server;
Enable transmission of tthe aforementioned metadata to patient records existing on the current EAP platform.
