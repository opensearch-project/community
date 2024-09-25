# Technical Charter

Technical Charter (the "Charter") for OpenSearch Project a Series of LF Projects, LLC

_Adopted September 13, 2024_

This Charter sets forth the responsibilities and procedures for technical contribution to, and oversight of, the OpenSearch Project open-source project, which has been established as OpenSearch Project a Series of LF Projects, LLC (the "Project"). LF Projects, LLC ("LF Projects") is a Delaware series limited liability company. All contributors (including committers, maintainers, and other technical positions) and other participants in the Project (collectively, "Collaborators") must comply with the terms of this Charter. 

1. **Mission and Scope of the Project**

   1. The mission of the Project is to develop an open-source search and analytics suite used by developers to perform various tasks, including but not limited to interactive log analytics, real-time application monitoring and website search, vector search for RAG and Generative A.I. use-cases, etc.

   2. The scope of the Project includes collaborative development under the Project License (as defined herein) supporting the mission, including documentation, testing, integration and the creation of other artifacts that aid the development, deployment, operation or adoption of the open-source project.

2. **Technical Steering Committee**

   1. The Technical Steering Committee (the "TSC") will be responsible for all technical oversight of the open-source Project. 

   2. Startup Period.

      1. The initial voting members ("Initial Members") of the TSC at the inception of the Project (the "Start Date") are those individuals identified as voting members in the "STEERING.md" file within the Project’s .github repository. Initial Members will consist of Initial Members serving one-year terms and Initial Members serving two-year terms, as indicated in the STEERING.md file.

   3. Steady State

      1. Approaching the first anniversary of the Start Date and for each anniversary thereafter, the TSC will call for elections from among active Project maintainers and leaders to succeed those voting members of the TSC whose terms are expiring (such elections, the "First Elections").   
         

      2. The then-current voting members of the TSC will be maintained in the "STEERING.md" file within the Project’s .github repository. Except in the case of vacancies that have been filled, all voting members of the TSC will serve two-year terms or until resignation or replacement. In the event that a voting TSC member ceases to be a voting TSC member for any reason, the TSC may appoint a successor voting member for the remainder of the applicable term. There are no term limits for voting members of the TSC.

   4. The TSC may choose an alternative approach for determining the voting members of the TSC, and any such alternative approach will be documented in the STEERING file in the .github repository. Absent specific considerations requiring a private meeting, meetings of the TSC are intended to be open to the public. TSC meetings can be conducted electronically, via teleconference or online meeting tool, and/or in person. 

   5. TSC projects generally will involve Contributors and Maintainers. The TSC may adopt or modify roles so long as the roles are documented in the .github repository documents . Unless otherwise documented: 

      1. Contributors include anyone in the technical community that contributes code, documentation, or other technical artifacts to the Project; 

      2. Maintainers are Contributors who have earned the ability to modify ("commit") source code, documentation or other technical artifacts in any of the project’s repositories; and  
           
      3. A Contributor may become a Maintainer by a majority approval of the existing Maintainers. A Maintainer may choose to step down from their function, or be removed by a ⅔ majority approval of the other existing Maintainers.

   6. Participation in the Project through becoming a Contributor and Maintainer is open to anyone so long as they abide by the terms of this Charter. 

   7. The TSC may (1) establish workflow procedures for the submission, approval, and closure/archiving of projects, (2) set requirements for the promotion of Contributors to Maintainer status, as applicable, and (3) amend, adjust, refine and/or eliminate the roles of Contributors, and Maintainers, and create new roles, and publicly document any TSC roles, as it sees fit.

   8. At the inception of the Project, the initial TSC Chair will be that Initial Member indicated in the STEERING.md file in the Project’s github repository as being the TSC Chair. As of the time of the First Election and annually thereafter, the TSC will elect a TSC Chair. The TSC Chair will preside over meetings of the TSC and will serve until their resignation or replacement by the TSC. The TSC Chair, or any other TSC member so designated by the TSC, will serve as the primary communication contact between the Project and OpenSearch Foundation, a directed fund of The Linux Foundation.

   9. Responsibilities: The TSC will be responsible for all aspects of oversight relating to the Project, which may include:

      1. coordinating the technical direction of the Project;

      2. approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope);

      3. organizing sub-projects and removing sub-projects;

      4. creating sub-committees or working groups to focus on cross-project technical issues and requirements;

      5. appointing representatives to work with other open source or open standards communities;

      6. establishing community norms, workflows, issuing releases, security issue reporting policies and the Elections Procedures Document (defined below);

      7. approving and implementing policies and processes for contributing (to be published in the CONTRIBUTING file) and coordinating with the series manager of the Project (as provided for in the Series Agreement, the "Series Manager") to resolve matters or concerns that may arise as set forth in Section 7 of this Charter;

      8. discussions, seeking consensus, and where necessary, voting on technical matters relating to the code base that affect multiple projects; and

      9. coordinating any marketing, events, or communications regarding the Project.

3. **TSC Voting**

   1. While the Project aims to operate as a consensus-based community, if any TSC decision requires a vote to move the Project forward, the voting members of the TSC will vote on a one vote per voting member basis.

   2. Quorum for TSC meetings requires at least fifty percent of all voting members of the TSC to be present. The TSC may continue to meet if quorum is not met but will be prevented from making any decisions at the meeting.

   3. Except as provided in Section 7.c. and 8.a, decisions by vote at a meeting require a majority vote of those in attendance, provided quorum is met. Decisions made by electronic vote without a meeting require a majority vote of all voting members of the TSC.

   4. In the event a vote cannot be resolved by the TSC, any voting member of the TSC may refer the matter to the Series Manager for assistance in reaching a resolution.

   5. With respect to elections, the TSC may maintain an election procedures document (the "Election Procedures Document") which will set forth requirements, procedures and other details with respect to how the TSC runs elections.

4. **Compliance with Policies** 

   1. This Charter is subject to the Series Agreement for the Project and the Operating Agreement of LF Projects. Contributors will comply with the policies of LF Projects as may be adopted and amended by LF Projects, including, without limitation the policies listed at https://lfprojects.org/policies/. 

   2. The TSC may adopt a code of conduct ("CoC") for the Project, which is subject to approval by the Series Manager. In the event that a Project-specific CoC has not been approved, the LF Projects Code of Conduct listed at [https://lfprojects.org/policies](https://lfprojects.org/policies) will apply for all Collaborators in the Project.

   3. When amending or adopting any policy applicable to the Project, LF Projects will publish such policy, as to be amended or adopted, on its web site at least 30 days prior to such policy taking effect; provided, however, that in the case of any amendment of the Trademark Policy or Terms of Use of LF Projects, any such amendment is effective upon publication on LF Project’s web site.

   4. All Collaborators must allow open participation from any individual or organization meeting the requirements for contributing under this Charter and any policies adopted for all Collaborators by the TSC, regardless of competitive interests. Put another way, the Project community must not seek to exclude any participant based on any criteria, requirement, or reason other than those that are reasonable and applied on a non-discriminatory basis to all Collaborators in the Project community.

   5. The Project will operate in a transparent, open, collaborative, and ethical manner at all times. The output of all Project discussions, proposals, timelines, decisions, and status should be made open and easily visible to all. Any potential violations of this requirement should be reported immediately to the Series Manager.

5. **Community Assets**

   1. LF Projects will hold title to all trade or service marks used by the Project ("Project Trademarks"), whether based on common law or registered rights. Project Trademarks will be transferred and assigned to LF Projects to hold on behalf of the Project. Any use of any Project Trademarks by Collaborators in the Project will be in accordance with the license from LF Projects and inure to the benefit of LF Projects. 

   2. The Project will, as permitted and in accordance with such license from LF Projects, develop and own all Project GitHub and social media accounts, and domain name registrations created by the Project community.

   3. Under no circumstances will LF Projects be expected or required to undertake any action on behalf of the Project that is inconsistent with the tax-exempt status or purpose, as applicable, of the Joint Development Foundation or LF Projects, LLC.

6. **General Rules and Operations.** 

   1. The Project will:

      1. engage in the work of the Project in a professional manner consistent with maintaining a cohesive community, while also maintaining the goodwill and esteem of LF Projects, Joint Development Foundation and other partner organizations in the open source community; and

      2. respect the rights of all trademark owners, including any branding and trademark usage guidelines.

7. **Intellectual Property Policy**

   1. Collaborators acknowledge that the copyright in all new contributions will be retained by the copyright holder as independent works of authorship and that no contributor or copyright holder will be required to assign copyrights to the Project. 

   2. Except as described in Section 7.c., all contributions to the Project are subject to the following: 

      1. All new inbound code, documentation and other contributions to the Project must be made using Apache License, Version 2.0 available at http://www.apache.org/licenses/LICENSE-2.0 (the "Project License"). 

      2. All new inbound code, documentation and other contributions must also be accompanied by a Developer Certificate of Origin ([http://developercertificate.org](http://developercertificate.org)) sign-off in the source code system that is submitted through a TSC-approved contribution process which will bind the authorized contributor and, if not self-employed, their employer to the applicable license;

      3. All outbound code, documentation and other contributions will be made available under the Project License.

      4. The Project may seek to integrate and contribute back to other open source projects ("Upstream Projects"). In such cases, the Project will conform to all license requirements of the Upstream Projects, including dependencies, leveraged by the Project. Upstream Project code contributions not stored within the Project’s main code repository will comply with the contribution process and license terms for the applicable Upstream Project.

   3. The TSC may approve the use of an alternative license or licenses for inbound or outbound contributions on an exception basis. To request an exception, please describe the contribution, the alternative open source license(s), and the justification for using an alternative open source license for the Project. License exceptions must be approved by a two-thirds vote of the entire TSC. 

   4. Contributed files should contain license information, such as SPDX short form identifiers, indicating the open source license or licenses pertaining to the file.

8. **Amendments**

   1. This charter may be amended by a two-thirds vote of the entire TSC and is subject to approval by LF Projects.

