
----

# Summary 

The “Amazonian Ecosystem” is an ontology directed to the general public with the aim to help people have access, via a structured logical system, to accurate information describing the complex interrelationship of the many kinds of living organisms existing in the Amazonian Rainforest. 
Due to its general public aim, this ontology is not based on the taxonomic scientific structure of species, which is the approach chosen by most bio-ontologies. Animals and plants are referred to by their common names. Although not done by us, this design is compatible with the addition of a taxonomic structure on the species and we can always provide information about its scientific name via comments.

The Amazonian Ecosystem is extremely vast and complex. As being so, an exhaustive ontology on its species is a monumental task that was not possible within hour time/labor constraints. Our ontology contains 1722 axioms and 266 classes and focuses more on Animals and their food chain relationship, but also contains information about their size, medium of locomotion, defense mechanisms, their habitats and much more. In this ontology we preferred species whose information were readily available on multiple sources, so in some sense we covered the “most popular” species on the Amazonia.

In the spirit of the ONU goals 14 and 15 about, respectively, life underwater and on ground we provide information about endangered species being guided by the  IUCN Red List, a system that divides the risk of extinction of a species in, mainly, 8 categories: Extinct, Extinct in the WIld, Critically endangered, Endangered, Vulnerable, Near Threatened, Conservation Dependent, Least Concern. By incorporating this information with the knowledge of food chain interactions we can infer which species might be affected by the extinction of a given species. The class FoodChainDependentOnEndangeredSpecies is an example of one inference that goes in this sense.

Interesting classes to look for inference are: Diet, EndangeredSpecies, FoodChain,HasSymbioticMutalRelationship, Apex Predator and Habitat.

# Guidelines

## A. Basics

### A.1 Ontology name

|                  | Specification       |
| ---------------- | ------------------- |
| **Description:** | Amazonian Ecosystem |
----


### A.6 Methodological framework

|                  | Specification                                                                                                                                                                                                                                                                                                                                                         |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description:** | This ontology was developed by a group of three. We decided together the scope and the structure of the database and the references we were going to use. Then we filled in parallel the ontology with the information we collected. There were a few sessions were adapted and restructured the ontology as we got more information and experience with the subject. |
At the end we spent time verifying the consistency and the veracity of the data.
 |

----

## B. Motivation

### B.1 Need

|                  | Specification                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Description:** | Justification of why the ontology is required.                                                                                                                                                                                                                                                                                                                                                   |
| **Importance:**  | MUST                                                                                                                                                                                                                                                                                                                                                                                             |
| **Example:**     | For example, the 2015 JBMS article "Unification of multi-species vertebrate anatomy ontologies for comparative biology in Uberon" has the following: "Here we present the unification of anatomy ontologies into Uberon, a single ontology resource that enables interoperability among disparate data and research groups." http://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-5-21 |
----

### B.2 Competition

|                  | Specification                                |
| ---------------- | -------------------------------------------- |
| **Description:** | There have been many bio-ontologies proposed Like the Wildlife Ontology and the Animal trait ontology.But there was no ontology that focused on the Amazonian Ecosystem|

                                                                                                       |

----

### B.3 Target audience

|                  | Specification |
| ---------------- | ------------- |
| **Description:** |
The general public that is interested in knowing and understanding the richness of the amazon ecosystem.
                                                                                      
----

## C. Scope, requirements, development community

### C.1 Scope and coverage

|                  | Specification                                                                                                                                                                                                                                                                                                                        |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Description:** | This ontology covers information of the Animals and Plants that exist in the Amazon rainforest. These species were selected based on the ease of obtaining information about them, so in some sense it covers the most popular species, but it is no way extensive. We covered the most we were able to, on our limited time budget. |
----



## D. Knowledge acquisition

### D.1 Knowledge acquisition methodology

|                  | Specification                                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Description:** | Our knowledge acquisition methodology was to search authoritative sources on the internet and double check different sources when possible. |
                                             
----

### D.2 Source knowledge location

|                  | Specification                                                 |
| ---------------- | ------------------------------------------------------------- |
| **Description:** | The location of the source whence the knowledge was gathered. |
----
## E. Ontology content


### E.3 Ontology metrics

|                  | Specification                                                 |
| ---------------- | ------------------------------------------------------------- |
| **Description:** | 1753 axioms  265 classes 925 SubClassOf   22 ObjectProperties |
|                  |                                                               |

----


### E.9 Ontology relationships

|                  | Specification                                  |
| ---------------- | ---------------------------------------------- |
| **Description:** | hasPrey: Describes if a predator has some prey, eatsofPlant: Describes if an animal eats a kind a plant, pollinates: If an animal pollinates a plant |
----

## G. Quality Assurance

### G.1 Testing

|                  | Specification                                                      |
| ---------------- | ------------------------------------------------------------------ |
| **Description:** | The ontology has been checked to be consistent using Hermit 1.4.3. |
Examples of inferences:Carnivore,Apex Predator, EndangereSpecies
 |

----
