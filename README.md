## Mini TP: Hello, world!
### Lors de ce TP vous devrez :

- Créer un repository vierge
- Y enregistrer votre runner pour qu'il soit en mesure d'exécuter une pipeline de CI/CD, attention, choisissez au moins un tag
- Créer un fichier .gitlab-ci.yml contenant:
- Une section stages contenant un simple stage hello-world
- Une section hello, faisant référence au stage hello-world, et exécutant le script "echo Hello, world!", pensez à rajouter une sous section tags pour que votre runner intercepte le job
- Lors du commit, la pipeline devrait se lancer et être disponible dans l'onglet "CI/CD => Pipelines"

## Livrables :
  Votre log de pipeline indiquant "Hello, World!"
