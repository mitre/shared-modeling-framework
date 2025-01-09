## Shared Modeling Framework

The Shared Modeling Framework for Mission Engineering is an approach developed by MITRE to address the rapidly evolving challenges faced by mission engineers. This framework is designed to promote standardization, reusability, and efficiency in mission model development, leveraging a structured methodology that minimizes the need for repeated development from scratch. This framework includes: the Seed Model, which serves as a foundational blueprint containing generic properties for a class of systems; and the Base Model, which specifies properties for specific systems inherited from the Seed Model. By utilizing objects (or "Blocks" in SysML) and inheritance relationships, the framework allows for the same Block to be instantiated across various mission architectures, significantly reducing the effort required to construct new models. This framework was built from the ground up using openly published standards to enable the development of mission engineering architecture models for many different application domains. The framework is intended to be extensible so that additional standards can be integrated as needed.

## Getting Started
- Obtain released version of Base Model and Seed Model by downloading the [Base Model File](https://github.com/mitre/shared-modeling-framework/blob/main/MagicDrawFiles/Shared%20Modeling%20Framework/Base_Model_3.0.mdzip) and [Seed Model File](https://github.com/mitre/shared-modeling-framework/blob/main/MagicDrawFiles/Shared%20Modeling%20Framework/Seed_Model_3.0.mdzip).
- To use the Base Model, open up Cameo/MagicDraw and select “Use Project > Use Local Project” from the File menu within your Mission Model project of interest and navigate to the downloaded Base Model File. Additionally, load your downloaded Seed Model File.
- Now you are ready to use the Shared Modeling Framework. To reuse a building block or element from the Base Model, create an element in your Mission Model and establish a “generalization” relationship to the corresponding element in the Base Model.
- To see an example of how to do these steps, please refer to this [recording](https://github.com/mitre/shared-modeling-framework/blob/main/Guides%20and%20Learning%20Materials/SMF_Example_Recording.mp4).

## Issue Reporting and Enhancement Suggestions for the Shared Modeling Framework

To report an issue, suggest an enhancement, or ask a question regarding the Shared Modeling Framework, please submit a GitLab issue. When doing so, make sure you select the the appropriate template (e.g., enhancement_report, problem_report, question-report) from the description field drop-down. Please provide as much information as possible to help us understand and resolve the issue.

## Open Standards
The Shared Modeling Framework leverages the following open standards in the table below to enable seamless sharing and adoption by mission engineering architects:

| Standard Name | Standard Includes: | Was used for: |
| ---      | ---      | ---      |
| [SISO-REF-010-2020 and -2024](https://www.sisostandards.org/page/ReferenceDocuments) | Enumerated systems for Distributed Interactive Simulation (DIS)   | Extensive Base Model Entity List   |
| [MIL-STD-881F](https://quicksearch.dla.mil/qsDocDetails.aspx?ident_number=36026) | Framework for DoD Program Managers to define their program’s Work Breakdown Structure (WBS)  | Seed Model System Types and Possible Subsystems |
| [MIL-STD-196G](https://quicksearch.dla.mil/qsDocDetails.aspx?ident_number=35607)   |    Joint Electronics Type Designation Automated System (JETDAS) which is used to assign and manage type designations for electronic equipment and software within the DoD   | Nomenclature for electronic and associated equipment Electronics Categorization   |
| [DAF Instruction 16-401](https://static.e-publishing.af.mil/production/1/af_a8/publication/afi16-401/afi16-401.pdf) / Army Reg 70-50 / NAVAIRINST 13100.16 |    Guidelines and procedures for designating and naming Defense Military Aerospace Vehicles      | Aircraft and Missile Classifications   |
| [SECNAVIST 5030.8D](https://www.secnav.navy.mil/doni/Directives/05000%20General%20Management%20Security%20and%20Safety%20Services/05-00%20General%20Admin%20and%20Management%20Support/5030.8D.pdf) |  General Guidance for the Classification of Naval Vessels and Battle Force Ship Counting Procedures   | Naval Ship Designators   |

## Notice

Copyright 2024 The MITRE Corporation

SISO-REF-010-2024 is Copyright © 2024 by the Simulation Interoperability Standards Organization (SISO), Inc. Reprinted with permission from SISO Inc.

Approved for Public Release. Case Number 15-0050.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   <http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Reference Documents

The following references were used in the creation of the shared modeling framework:

Air & Space Forces Association. (n.d.). F-16 Fighting Falcon. Retrieved Nov 21, 2024, from Air & Space Forces Magazine: https://www.airandspaceforces.com/weapons-platforms/f-16/

BAE Systems. (n.d.). What are military and intelligence platforms? Retrieved Nov 20, 2024, from https://www.baesystems.com/en-us/definition/what-are-military-and-intelligence-platforms

DAU. (n.d.). Retrieved Nov 20, 2024, from DAU Glossary of Defense Acquisition Acronyms and Terms: https://www.dau.edu/glossary

Defense Industry Daily. (n.d.). Raytheon's ALE-50 "Little Buddy" Decoys. Retrieved Nov 21, 2024, from Defense Industry Daily: https://www.defenseindustrydaily.com/raytheons-ale50-little-buddy-decoys-02573/

Department of the Navy. (2022, June 28). SECNAV Instruction 5030.8D: General Guidance for the Classification of Naval Vessels and Battle Force Ship Counting Procedures. Retrieved Nov 20, 2024, from https://www.secnav.navy.mil/doni/Directives/05000%20General%20Management%20Security%20and%20Safety%20Services/05-00%20General%20Admin%20and%20Management%20Support/5030.8D.pdf

Dictionary.com, LLC. (n.d.). Retrieved Nov 20, 2024, from Dictionary.com: https://www.dictionary.com/

Elsevier. (n.d.). Radar Sensor. Retrieved Nov 20, 2024, from Science Direct: https://www.sciencedirect.com/topics/engineering/radar-sensor

Encyclopaedia Britannica. (n.d.). Retrieved Nov 20, 2024, from Britannica: https://www.britannica.com/

Encyclopaedia Britannica. (n.d.). Merriam-Webster Dictionary. Retrieved Nov 20, 2024, from Merriam-Webster Dictionary: https://www.merriam-webster.com/

Encyclopaedia Britannica, Inc. (n.d.). The Britannica Dictionary. Retrieved Nov 20, 2024, from https://www.britannica.com/dictionary
Headquarters, Department of the Army. (2024, February). FM 1-02.1 Operational Terms. Retrieved Nov 20, 2024, from Army Publishing Directorate: https://armypubs.army.mil/epubs/DR_pubs/DR_a/ARN40321-FM_1-02.1-000-WEB-2.pdf

International Organization for Standardization (ISO). (1994, Nov). ISO/IEC 7498-1:1994 - Information technology - Open Systems Interconnection - Basic Reference Model: The Basic Model. Retrieved from https://www.iso.org/standard/20269.html

Koretsky, G. M., Nicoll, J. F., & Taylor, M. S. (2013, Jan). Institute for Defense Analyses. Retrieved Nov 20, 2024, from A Tutorial on Electro-Optical/Infrared (EO/IR) Theory and Systems (D-4642): https://www.ida.org/-/media/feature/publications/a/at/a-tutorial-on-e-lectro--opticalinfrared-eoir-theory-and-systems/ida-document-d-4642.ashx

Law Insider, Inc. (n.d.). Legal Definitions Dictionary. Retrieved Nov 20, 2024, from https://www.lawinsider.com/dictionary

McClanahan, S. (2022, June 23). AESA radar launches F-16 into next generation of airpower. Retrieved Nov 21, 2024, from Air Force: https://www.af.mil/News/Article-Display/Article/3072483/aesa-radar-launches-f-16-into-next-generation-of-airpower/

NATO. (n.d.). Retrieved Nov 20, 2024, from NATO Term: The Official NATO Terminology Database: https://nso.nato.int/natoterm/content/nato/pages/home.html?lg=en

NIST. (n.d.). Definitions: Sensors. Retrieved Nov 20, 2024, from https://www.nist.gov/el/intelligent-systems-division-73500/definitions

Office of Naval Research. (n.d.). Directed Energy Weapons: Counter Directed Energy Weapons and High Energy Lasers. Retrieved Nov 20, 2024, from https://www.onr.navy.mil/organization/departments/code-35/division-353/directed-energy-weapons-cdew-and-high-energy-lasers

Oxford University Press. (n.d.). Retrieved Nov 20, 2024, from Oxford English Dictonary: https://www.oed.com/

Schweizer. (n.d.). Schweizer S333. Retrieved Nov 21, 2024, from https://schweizerrsg.com/new-helicopter/schweizer-333/

Simulation Interoperability Standards Organization (SISO), Inc. (2024). SISO-REF-010-2024: Reference for Enumerations for Simulation Interoperability. Retrieved Nov 20, 2024, from https://www.sisostandards.org/page/ReferenceDocuments

US Air Force. (n.d.). Retrieved Nov 21, 2024, from US Air Force Fact Sheets: https://www.af.mil/About-Us/Fact-Sheets/

US Department of Defense. (2014, May 16). Designating and Naming Defense Military Aerospace Vehicles: AF 16-401, Army Reg 70-50, NAVAIRINST 131001.16. Retrieved Nov 20, 2024, from https://static.e-publishing.af.mil/production/1/af_a8/publication/afi16-401/afi16-401.pdf

US Department of Defense. (2018, May 30). Department of Defense Standard Practice: Joint Electronics Type Designation Automated System: MIL-STD-196G. Retrieved Nov 20, 2024, from https://quicksearch.dla.mil/qsDocDetails.aspx?ident_number=35607

US Department of Defense. (2022, May 13). Department of Defense Standard Practice: Work Breakdown Structures for Defense Material Items: MIL-STD-881F. Retrieved Nov 20, 2024, from https://quicksearch.dla.mil/qsDocDetails.aspx?ident_number=36026

US Navy. (n.d.). Retrieved Nov 21, 2024, from Fact Files: https://www.navy.mil/Resources/Fact-Files/

US Navy. (n.d.). Retrieved Nov 21, 2024, from Naval Vessel Register: https://www.nvr.navy.mil/nvr/index.htm

US Navy. (n.d.). Retrieved Nov 21, 2024, from NAVAIR: https://www.navair.navy.mil/



