# Requirements

A client has hired you to track zoo animals.
For each individual animal, you must track that their name, species, and all zoos in which they have resided (including zoo name and address).

Determine the database tables necessary to track this information.

Label any relationships between table.

Tables: Animals, Species, Zoos

Animals (many) <==> Species (one)

Zoos (many) <==> Animals (many)

Species:

- id
- species_name

Animals:

- id
- name
- species_id

Zoos:

- id
- zoo_name
- zoo_address

zoo_animals

- zoo_id
- animal_id
