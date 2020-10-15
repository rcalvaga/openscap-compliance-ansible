
Adding a Survey
=======================
A survey allows us to change the job template behaviour by changing the variable answers in a human readable form.

Step 1:
-------

Select **Templates**

Step 2:
-------

Click our Openscap_scan job template and then click on the ![Add_Survey](images/add_survey.png) icon.

Step 3:
-------
Complete the survey form with following values

| Key                     | Value                                                                                                                                                  | Note                                         |
|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------|
| PROMPT                  | Security Compliance Profile to Run                                                                                                                                             |                                              |
| DESCRIPTION             | Which Security compliance profile should we scan for?                                                                                                                           |                                              |
| ANSWER VARIABLE NAME    | ssg_profile                                                                                                                                             |                                              |
| ANSWER TYPE             | Multiple Choice (single select)                                                                                                                      | **There's also a *single* selection option** |
| MULTIPLE CHOICE OPTIONS |  xccdf_org.ssgproject.content_profile_ospp<br>xccdf_org.ssgproject.content_profile_pci-dss<br>xccdf_org.ssgproject.content_profile_stig<br>xccdf_org.ssgproject.content_profile_e8 |                                              |
| DEFAULT ANSWER          |  xccdf_org.ssgproject.content_profile_pci-dss                                                                                                                       |                                              |
| REQUIRED                | Selected                                                                                                                                               |                                              |
|                         |                                                                                                                                                        |                                              |


Once complete, click the ADD ![Add](images/at_add.png) button.


