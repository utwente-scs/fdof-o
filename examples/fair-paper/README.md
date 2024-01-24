# FAIR Paper GPT Example

This folder contains a FDOF example where the seminal paper [The FAIR Guiding Principles for scientific data management and stewardship](https://www.nature.com/articles/sdata201618), by Wilkinson et al., is described as a FAIR Digital Object. The files in this folder have been fed to GPT-4 which was then used to produce descriptions of the digital objects of this example in terms of FDOF. The following list of files has been used in this process:

- `fair-paper.trig`: TriG file containing examples of FAIR digital objects related to the seminal FAIR paper.
- `fdof-o.ttl`: Turtle file of the [FDOF-O](../../owl/fdof-o.ttl) ontology.
- `fdof-t.ttl`: Turtle file containing the digital object types defined alongside FDOF-O, the [FDOF-T](../../owl/fdof-t.ttl) ontology.
- `fdof-paper.pdf`: [arVix preview](https://doi.org/10.48550/arXiv.2302.11894) of the [FDOF paper](https://doi.org/10.3233/FAIA231131) presented at FOIS 2023.
- `fdof-framework-documentation.html`: HTML documentation of the [FAIR Digital Object Framework](https://fairdigitalobjectframework.org/).
- `dcat2.ttl`: Turtle file of the [DCAT 2](https://www.w3.org/ns/dcat2.ttl) vocabulary.
- `dcat2.html`: HTML documentation of the [DCAT 2](https://www.w3.org/TR/vocab-dcat-2/) vocabulary.

## Contributors
- Luiz Olavo Bonino da Silva Santos
- Claudenir Moraes Fonseca
- Tiago Prince Sales
- Giancarlo Guizzardi
- Barend Mons

## Prompts and answers from GPT-4 enriched with FDOF relevant files

The entire with GPT-4 can be found [here](https://chat.openai.com/share/971ff585-0d90-42d2-8c72-e0b8a4452305) and in the [`gpt-4-prompts.pdf`](./gpt-4-prompts.pdf) file.

### 1. Process these files. Consider the presence of named graphs in the .trig file. At the end, give me a description of FDOF.

> The "FAIR Digital Object Framework (FDOF)" is a model for representing and managing digital objects in a digital environment. It includes mechanisms for creating, maintaining, and reusing these objects. Key components of FDOF are a predictable identifier resolution behavior, a method for retrieving an object's metadata, and an object typing system. The primary objective of FDOF is to support the FAIR principles (Findability, Accessibility, Interoperability, and Reusability) by defining features essential for these principles. FDOF allows digital objects to be identified by unique, persistent, and resolvable identifiers, described by metadata records (which are FAIR Digital Objects themselves), and classified by the FDOF typing system. This framework is significant for enhancing the interoperability and reusability of digital objects in various fields, particularly in scientific and research data management.


### 2. Give me a description of https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaper in terms of FDOF.

> I encountered an error while attempting to query the fair-paper.trig file for the description of the resource "https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaper" in terms of the FAIR Digital Object Framework (FDOF). The error message is "can't set attribute."
> 
> This issue seems to be related to the querying process. I'll try a different approach to extract the required information. ​​
> 
> The resource "https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaper" is described in the fair-paper.trig file with the following properties in terms of the FAIR Digital Object Framework (FDOF):
> 
> * **Type of Information Object**: It is classified as an Article under the FDOF type system (https://w3id.org/fdof/types#Article).
> 
> * **Metadata**: It is associated with multiple metadata representations:
>   * FDOF Metadata (https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperFdofMetadata).
>   * Nature Metadata (https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperNatureMetadata).
> 
> * **Identifiers**: It has two identifiers associated with it:
>   * A Nature article link (https://www.nature.com/articles/sdata201618).
>   * A DOI link (https://doi.org/10.1038/sdata.2016.18).
> 
> * **Materialization**: It is materialized by different formats:
>   * HTML Metadata (https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperHtmlMetadata).
>   * PDF Metadata (https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperPdfMetadata).
> 
> * **Type**: It is defined as an InformationObject in the FDOF ontology (https://w3id.org/fdof/ontology#InformationObject).
> 
> These properties provide a comprehensive view of how the resource is represented and managed within the FDOF framework, demonstrating its adherence to the FAIR principles. ​​

### 3. Give me now a one-paragraph description of https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaper in terms of FDOF.

> The resource "https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaper" within the FAIR Digital Object Framework (FDOF) is a notable example of an Information Object, specifically categorized as an 'Article' under FDOF's type system. This resource is uniquely identified by two identifiers: a Nature article link and a DOI, ensuring its findability and accessibility. It features diverse metadata representations, including FDOF Metadata, Nature Metadata, and is materialized in various formats like HTML and PDF, highlighting the framework's commitment to interoperability and reusability. These attributes collectively underscore the resource's alignment with the FAIR principles, exemplifying how digital objects can be efficiently managed, shared, and utilized in a digital ecosystem under the FDOF model.

### 4. Give me a description of https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperFdofMetadata in terms of FDOF.

> The resource "https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperFdofMetadata" within the FAIR Digital Object Framework (FDOF) represents the metadata for the "FAIR Principles Paper". This resource is characterized as follows in terms of FDOF:
> 
> 1. **Information Object Type**: It is categorized as 'ArticleMetadata' (https://w3id.org/fdof/types#ArticleMetadata), indicating that it serves as metadata for an article.
> 
> 2. **Title**: The title of this metadata resource is "FAIR paper metadata available as an FDOF example".
> 
> 3. **Association with the FAIR Principles Paper**: It is directly linked as metadata of the "FAIR Principles Paper" (https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaper), establishing a clear relationship between the metadata and its associated digital object.
> 
> 4. **Unique Identifier (GUPRI)**: It is identified with a unique identifier or GUPRI (https://w3id.org/fdof/examples/fair-paper#paperFdofMetadata), which ensures its distinct and resolvable identity within the framework.
> 
> 5. **Materialization**: This metadata is materialized by a specific resource (https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig), indicating the format or manifestation of the metadata.
> 
> 6. **Type**: It is classified as a 'FAIRMetadataRecord' (https://w3id.org/fdof/ontology#FAIRMetadataRecord) in the FDOF ontology, signifying its role as a metadata record adhering to the FAIR principles.
> 
> These properties collectively illustrate how the resource is integrated and utilized within the FDOF framework, emphasizing its role in supporting the findability, accessibility, interoperability, and reusability of the associated digital object.


### 5. Give me now a one-paragraph description of https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperFdofMetadata in terms of FDOF.

> The resource "https://w3id.org/fdof/examples/fair-paper#fairPrinciplesPaperFdofMetadata" in the FAIR Digital Object Framework (FDOF) serves as a specialized metadata record for the "FAIR Principles Paper". Classified as 'ArticleMetadata' within FDOF's typology, it is uniquely identified by a specific GUPRI, enhancing its findability and accessibility in digital environments. This metadata record, titled "FAIR paper metadata available as an FDOF example", establishes a direct linkage to its corresponding digital object, the "FAIR Principles Paper", thereby exemplifying the interconnected nature of metadata and data in FDOF. Furthermore, its materialization through a dedicated resource emphasizes the framework's commitment to interoperability and reusability. As a 'FAIRMetadataRecord', it embodies the principles of the FAIR framework, playing a crucial role in the structured and efficient management of digital information objects.


### 6. Give me a description of https://w3id.org/fdof/examples/fair-paper#trigMetadata in terms of FDOF.

> The resource "https://w3id.org/fdof/examples/fair-paper#trigMetadata" within the FAIR Digital Object Framework (FDOF) is an instance of 'FAIRMetadataRecord', specifically focusing on the metadata in the Trig format. This resource is characterized as follows in terms of FDOF:
> 
> 1. **Materialization**: It is materialized by the resource "https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig", indicating the specific format or manifestation of this metadata.
> 
> 2. **Information Object Type**: Classified as 'TrigMetadata' (https://w3id.org/fdof/types#TrigMetadata), it signifies that this metadata is in the Trig (TriG) format, a serialization format for RDF (Resource Description Framework) data.
> 
> 3. **Type**: As a 'FAIRMetadataRecord' (https://w3id.org/fdof/ontology#FAIRMetadataRecord), it fulfills the role of a metadata record adhering to the FAIR principles, highlighting its importance in ensuring the metadata's findability, accessibility, interoperability, and reusability.
> 
> 4. **Unique Identifier (GUPRI)**: The resource is identified with a GUPRI (https://w3id.org/fdof/examples/fair-paper#trigMetadata), ensuring its unique identification and resolvability within the digital environment.
> 
> 5. **Association with Trig Metadata**: It is linked as metadata of the "https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig" resource, establishing a clear relationship between the metadata and its associated digital object.
> 
> This description underlines the resource's integration in the FDOF framework, emphasizing its structured approach to managing digital metadata in a manner that aligns with the FAIR principles. ​


### 7. Give me a one-paragraph description of https://w3id.org/fdof/examples/fair-paper#trigMetadata in terms of FDOF.

> The resource "https://w3id.org/fdof/examples/fair-paper#trigMetadata" in the FAIR Digital Object Framework (FDOF) represents a distinctive type of metadata, specifically tailored for the Trig (TriG) format. As a 'FAIRMetadataRecord', it embodies the core principles of FAIR — Findability, Accessibility, Interoperability, and Reusability — within its domain. Classified under 'TrigMetadata', it highlights its specialization in a format that supports RDF data serialization. This resource is uniquely identifiable through its GUPRI, facilitating its seamless integration and retrieval in digital environments. Additionally, it maintains a direct association with the "https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig" resource, signifying its role in providing comprehensive metadata for the associated digital object. Through these characteristics, the resource exemplifies the FDOF's commitment to creating a structured, efficient, and interoperable digital information landscape.


### 8. Give me a description of https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig in terms of FDOF.

> The resource "https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig" within the FAIR Digital Object Framework (FDOF) is identified as a 'FAIRMediaObject'. This classification highlights its role as a media object adhering to the principles of findability, accessibility, interoperability, and reusability. Key attributes of this resource are:
> 
> 1. **Type**: It is defined as a 'FAIRMediaObject' (https://w3id.org/fdof/ontology#FAIRMediaObject), indicating its role as a media object within the FDOF framework, focusing on adhering to FAIR principles.
> 
> 2. **Encoding Format**: The resource has an encoding format specified as 'application/trig' (https://www.iana.org/assignments/media-types/application/trig), which denotes its format type as Trig, a serialization for RDF data.
> 
> 3. **Identifier**: It possesses a unique identifier (https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig), ensuring that it can be distinctly recognized and accessed within the digital environment.
> 
> These characteristics collectively emphasize the resource's integration into the FDOF framework, underscoring its significance in managing digital media objects in a structured, standardized, and FAIR-compliant manner.


### 9. Give me a one-paragraph description of https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig in terms of FDOF.

> The resource "https://w3id.org/fdof/examples/fair-paper#paperMetadataTrig" in the FAIR Digital Object Framework (FDOF) exemplifies a 'FAIRMediaObject', a classification that underscores its adherence to the FAIR principles of findability, accessibility, interoperability, and reusability in the realm of digital media objects. This resource is specifically characterized by its encoding format as 'application/trig', denoting its specialization in the Trig format, which is a serialization for RDF (Resource Description Framework) data. The unique identifier associated with this resource ensures its distinct recognition and accessibility within digital environments. As a 'FAIRMediaObject', it represents a critical component in the FDOF ecosystem, embodying the framework's commitment to structuring and managing digital media objects in a standardized, efficient, and FAIR-compliant manner.
