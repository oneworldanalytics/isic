
# isic

<!-- badges: start -->
<!-- badges: end -->

The goal of isic is to provide an application that combines the International Standard Industrial Classification (version 4) with the Central Product Classification (CPC version 2.1) and
make it available in an accessible way. The application will be updated for the new ISIC5 and the draft CPC version 3

The classifications we are using can be located at the UN here: https://unstats.un.org/unsd/classifications/unsdclassifications

### Notes

Relevant datasets and documentation are in the data folder

- csv and excel files with the name structure are the main datasets
- there is a join table between the CPC2.1 and ISIC4 in the data/CPC2-ISIC4 folder. We normally want to keep the full ISIC and 
so expect to use a left join from ISIC to the other sets. 

### Tasks

1. Work out how to join the ISIC and CPC tables together using pandas or similar ensuring that all the elements of 
the ISIC4 classification are retained when joining.
2. Explore the use of LangChain with Python [https://www.langchain.com/](https://www.langchain.com/) by installing 
and identifying relevant walkthroughs and tutorials
3. Identify the best way to use AI to make information on the classifications and the relationships between them
searchable and usable by a wider audience.
  - Do you need a backend? (e.g. a database)
  - Are API calls needed?
  - Do you need a front end (e.g Streamlit)
4. Try different approaches using LangChain to identify effective means of communicating with the wider audience
5. Ensure that the approach includes validation that what the AI application is producing is factually true. The outcome must be factually true.


