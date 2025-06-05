---
title: Data Management Plan
layout: page
permalink: /dmp.html
---

**Data Management Plan** 

**Project Description**  

Our collection for this term focuses on ancient Greek statues and busts, with an emphasis on depictions of prominent mythological figures of relevant Greek Gods. These works can be dated from the Archaic period (c. 500 BCE) through the Hellenistic period (as late as 10 BCE). While also including some pieces that transition into early Roman times (27 BCE–14 CE). All of these show some pieces that depict early Greek civilization. Each item in our collection includes information like name, time period, location, and creator. This theme is important because it shows how ancient Greeks saw their gods and overall heros. Portraying their beauty, heroism, and divinity. This collection can analyze trends overtime of style features and visualization of Greek Gods. We want to avoid having duplicates in our collection to show a very broad range of different figures and gods across Greek culture and time periods. 

The intended audience of this collection would be high school and college instructors of art history or world history realms. A high school teacher could use this collection to help their students visualize Greek Gods during a mythology section, while a college professor could show the changes from various time periods. The students can also analyze the differences in sculpting techniques by location or time period as well. All of these items in our collection come from public domain museum archives and university digital repositories like The British Museum. Our descriptions of our items are meant to give a brief description of the type of sculpture and exactly what the creator was attempting to portray their god doing. All in hopes to give our target audiences a better overview and informative idea for that item.

**Anticipated Data**

We had gathered our data from primarily European Museum Collections, catalogs, and databases. We started by going through each collection and grabbing the main gods and deities like Zeus and Aphrodite who are prominent in Greek god history. Then categorizing the data by what it was made by and making sure to look in the description for creators mentioned, where it was made, and time periods. This data that was acquired could be in the form of JPEG/JPG or a pdf if that format is allowed. We will record our data in sheets format that will easily convert to a CSV for analysis and easy transfer to GitHub. 

|Item Description|File Type|Size (in MB)|\# of Items|License(s)|Sources|
|---|---|---|---|---|---|
|Screen grabs and downloaded images of sculptures from european museum collections|jpg/jpeg|3.9|21 Items|Creative Commons Zero - Public Domain|British Museum, National Archeological Museum, Met Museum, MFA Boston, National Museums Liverpool, Newfields, Heraklion Archaeological Museum|

**Documentation and Metadata**

All documentation for this project, including our data dictionary, will be made available through both a public GitHub repository and our GitHub-hosted Collection Builder Data website. This data dictionary gives clear definitions for each of our variables in our dataset with some units of measurement. This allows for an easier accessibility and reusability for other researchers and teachers. The GitHub repository is openly accessible and will be linked in our published materials and presentations. If need be, users can view, download, and contribute to the documentation as needed.

**Storage and Backup**

All images are stored in Google Drive and GitHub and can be reaccessed via the metadata sheet (saved within the Google Drive Cloud), which includes the source links. The repository is stored on GitHub. 

**Data Sharing**

The dataset and its supporting materials are publicly shared through both a GitHub repository and an accompanying GitHub Pages website. Our GitHub repository houses our full dataset while our GitHub website presents our data in a visually accessible public format for all users. Data can also be downloaded directly through the CollectionBuilder website interface. All materials are released under a Creative Commons Attribution 4.0 International (CC BY 4.0) license, allowing for open reuse with proper attribution. We encourage use by researchers in digital humanities, classical studies, and museum curation, as well as educators and the general public.

**Period of Data Retention**

We plan to retain all components of our project including our dataset, documentation, and our GitHub pages website for as long as possible after the completion of our DSCI 350 course at the University of Oregon. Our project will remain accessible for future references, portfolio uses, and for any users who want to use it for academic or professional opportunities. We plan to keep data on GitHub indefinitely, with  periodic checks (about once a year) to ensure that the website and repository remain functional and accessible. This allows for long-term access and archiving. If no future updates are planned by either creator, the repository will be placed into GitHub’s archived state with a clear indication of the project's completion date and final status. 

**Licensing and Ethical Issues**

The images used in this collection are all fair use, as they are in the public domain. We ensured that we cited the sources from which we obtained the images and provided ample context, including the creators and dates where possible. We do not anticipate any ethical issues with this project and do not claim ownership of any of the images used in this collection. 

**Appendix: Data Dictionary**  

|**field**|**definition**|**example value**|
|---|-----------------------------|---------------------------------------------|
|objectid|For our object IDs, we used a basic coll000 labeling system. The objects are in no particular order|coll010|
|filename|Files we named using title case and contain the material used and the god/goddess noted|Colossal_Head_of_Artemis.jpg|
|title|The title naming scheme is simple: the name(s) of the god(s) or goddess(es)|Artemis|
|creator|The creator is the name of the creator/sculptor, if known and labeled on the object’s museum page|Damophon|
|location|The location is either specific or broad, depending on the object, its age, and the museum’s citations of the object’s origin|Lykosoura, Arcadia|
|date|The estimated creation date for the object. When the object is dated by a range of years, we took the middle of the range and listed it as “date.” The date range can be found in the “date_range” section. The date is in BCE or CE, standing for “Before Common Era” and “Common Era” respectively|185 BCE|
|date_range|The date_range value is an estimated creation date range that was provided by the museum source. From objects that did not have a date range but did have a single year listed, that single number would be in both the “date” and “date_range” sections|190-180 BCE|
|description|The description describes the object in more detail and mentions the god/goddess, the material the statue is made of, and the art period that the object is from|Marble statuette of the goddess Artemis from the Hellenistic period.|
|subject|The subject is a list of attributes of the statue, separated by a semicolon, and written in lowercase, except for the name of the god or goddess. The three main subjects in this collection are the names of the god or goddess, whether they’re a god or a goddess, and the material that the statue is made out of|Artemis;goddess;marble|
|source|The source is a link to the museum website section for the object|National Archaeological Museum, Hellenistic Period, Image 1, https://www.namuseum.gr/en/collection/ellinistiki-periodos-2/|
|format|The format of our collection is digital and photographs. Therefore, we used images/JPEGs|image/jpeg|
|rights|The rights is the Creative Commons Zero since all of the statues featured in this collection are in the public domain|Creative Commons Zero|
|rightsstatement|The rights statement is a link to the public domain information through Creative Commons|https://creativecommons.org/publicdomain/zero/1.0/|
