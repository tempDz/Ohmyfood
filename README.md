<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descriptif Ohmyfood</title>
</head>
<body>
    <h1>Ohmyfood!</h1>
    <h2>Troisième projet Openclassroom - Développeur Web</h2>
    <h3>Scénario :</h3>
    <p>Vous venez d’être recruté chez Ohmyfood!, en tant que développeur junior. Félicitations !

        Ohmyfood! est une jeune startup qui voudrait s'imposer sur le marché de la restauration. L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée. Finis, les temps d'attente au restaurant !</p>
        <p>Vous faites partie des 4 heureux élus qui ont la chance de travailler sur ce beau projet.

            L’équipe se compose de :
            
            Paul, le CTO du futur site ;
            Fanny, l’UX designer recrutée pour mettre le site aux couleurs de Paris ;
            Anissa, commerciale chargée de démarcher les restaurants ;
            et vous, chargé du développement du site.
            Anissa est en plein démarchage pour ce projet, auprès des restaurateurs. Elle vous interpelle à la machine à café :
            
            Tu connais pas la nouvelle ? Tu te rappelles le responsable commercial de ton resto préféré ? J’ai réussi à le convaincre, avec 3 autres, de déposer leurs cartes en ligne ! Je t’envoie le dossier avec les 4 menus dans l’après-midi. À toi de jouer, maintenant !
            
            Vous décidez alors, avec l’équipe, que le site contiendra 4 menus dans un premier temps. Voici le brief que vous établissez avec le CTO, Paul.
            
            De retour à votre bureau, vous trouvez un mail de Fanny qui vous envoie les maquettes du site.</p>
            <h3>Livrables attendus</h3>
            <h4>Page d’accueil (x1)</h4>
            <ul>
                <li><p>Affichage de la localisation des restaurants. À terme il sera possible de choisir sa
                    localisation pour trouver des restaurants proches d’un certain lieu.</p></li>
                <li><p>Une courte présentation de l’entreprise.</p></li>
                <li><p>Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,
                    l’utilisateur est redirigé vers la page du menu.</p></li>
            </ul>
            <h4>Pages de menu (x4)</h4>
            <ul>
                <li>4 pages contenant chacune le menu d’un restaurant.</li>
            </ul>
            <h4>Footer</h4>
            <ul>
                <li>Le footer est identique sur toutes les pages.</li>
                <li>Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.</li>
            </ul>
            <h4>Header</h4>
            <ul>
                <li>Le header est présent sur toutes les pages.</li>
                <li>Sur la page d’accueil, il contient le logo du site.</li>
                <li>Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil</li>
            </ul>
            <h3>Effets graphiques et animations</h3>
            <p>Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser
                les animations ou transitions CSS, pas de JavaScript ni de librairie.</p>
            <h4>Boutons</h4>
            <ul>
                <li>Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
                    L’ombre portée devra également être plus visible.</li>
                <li>À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
                    bouton "J’aime" en forme de coeur est présent sur la maquette. Au clic, il devra se
                    remplir progressivement. Pour cette première version, l’effet peut être apparaître au
                    survol sur desktop au lieu du clic.</li>
            </ul>
            <h4>Page d’accueil</h4>
            <ul>
                <li>Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
                    cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
                    3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
                    utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
                    toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
                    graphique du site.</li>
            </ul>
            <h4>Pages de menu</h4>
            <ul>
                <li>À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
                    décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
                    “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.</li>
                <li>Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
                    Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
                    la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
                    sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
                    des points de suspension. Un exemple de l’effet attendu est fourni.</li>
            </ul>
</body>
</html>
