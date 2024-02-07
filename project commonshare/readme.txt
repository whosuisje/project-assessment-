The project encompasses three primary components as follows:

Data Extraction from CERTIFIED SUPPLIERS DATABASE:
Initially, using Python alongside the BeautifulSoup library, we systematically retrieve the URLs of approximately 1000 companies listed within the CERTIFIED SUPPLIERS DATABASE. This step is crucial for establishing the foundation from which detailed company information will be extracted.

Data Collection from Extracted Links:
Subsequently, leveraging the previously obtained URLs, we meticulously extract a comprehensive set of data points for each company. The information extracted includes:

company: The official name of the company.
brand_name: The brand name associated with the company, where available.
country: The country, along with potential specific regions or cities, where the company is based.
product_category: The range of product categories the company is involved in, such as Fabrics, Babywear, Garments, Home Textiles, among others.
contact_name: The contact person’s name at the company.
email_address: The email address for reaching out to the company or the contact person.
address: The physical address of the company.
license_number: The unique license number tied to the company's certification or operational permit.
pdf: The URL pointing to a PDF document, which may contain details on the company's certification or other relevant information. Note that some entries in this category may be missing.
certification_body: The entity that has granted certification to the company.
expiry_date: The expiration date of the company's certification.
product_details: An in-depth description of the company's products, encapsulating specific types and categories.
Exploratory Analysis and Visualization:
Finally, an exploratory investigation is conducted within the database, aimed at deriving insightful visualizations that provide an overview of the Global Certification Landscape. This analysis seeks to uncover trends, patterns, and distributions that offer meaningful insights into the certification ecosystem, contributing to a better understanding of the global certification dynamics.

This structured approach not only facilitates the systematic gathering of critical data but also paves the way for a detailed understanding of the certification landscape.
the folder you will have :
the links that are been exctracted "links"
the database that contain the info "data"
a visualisation with power bi of the Global Certification Landscape with a pdf format and bi template (better to use bi template to interact with the data )
a csv with duplicate companies for the discovery process 
