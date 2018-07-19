# drupal8-mamc_navigart
Migration des œuvres de la connection du MAMC de Saint-Etienne depuis l'api navigart vers des entités media de drupal8.

Certains musées dont le Musée d'Art Moderne et Contemporain de Saint-Etienne utilisent le service Videomuseum pour la gestion de leur collection d'œuvres d'art. Ce service de gestion et de diffusion de collections met à disposition une API REST pour interroger la BDD. 

Ce module est un exemple d'import des données dans un drupal 8 utilisant les migrations (migrate, migrate_plus, migrate_tools et migrate_file). Ces données sont importées dans une entité media créée pour l'occase.
