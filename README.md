# MKTD12-My_Conference

## Objectif

Créer votre prope site de conférence.

Un site de conférence est au moins composé des éléments suivants :

- Un layout (menu, et footer).
- Une page d’accueil avec quelques photos (avec un carousel simple) et la liste des sponsors (hardcodée)
- La liste des speakers.
- Le planning de la conférence.
- Détail d’un talk.
- Une partie blog avec commentaires

Et… Tout ce que vous voulez ajouter d’autres 🙂

Exemple : https://hoverboard-master.web.app/ (https://github.com/gdg-x/hoverboard)

Si vous voulez, vous pouvez déployer votre site en ligne.

- Pour Qwik, voir https://qwik.dev/docs/deployments
- Pour NextJS, voir https://nextjs.org/docs/app/building-your-application/deploying

## API à votre disposition

### Liste des speakers

`GET https://konfetti.monkeypatch.io/web/conferences/demo-konfetti-2023/speakers`

Retourne un tableau de `Speaker`.

### Planning

`GET https://konfetti.monkeypatch.io/web/conferences/demo-konfetti-2023/schedule`

Retourne un `Schedule`.

### Détail d’une session

`GET https://konfetti.monkeypatch.io/web/conferences/demo-konfetti-2023/sessions/[id]`

Retourne un objet contenant une `Session`, une `Room` et une `Period`.

### Articles et commentaires

Voir les exercices de ce matin sur Supabase.
