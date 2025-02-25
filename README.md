# Spring-MVC---Gestion-des-Patients

<h1>Diagramme</h1>

<img src="Captures/diag.jpg">

<h2>Création de l'entité Patient</h2>

<img src="Captures/img1.jpg">

<p>L'entité Patient a été créée avec les attributs suivants :</p>

<ul>
    <li>id : de type Long, utilisé comme identifiant unique du patient.</li>
    <li>firstName : de type String, représentant le prénom du patient.</li>
    <li>lastName : de type String, représentant le nom de famille du patient.</li>
    <li>birthDate : de type LocalDate, représentant la date de naissance du patient.</li>
    <li>email : de type String, représentant l'adresse email du patient.</li>
</ul>

<h2>Création du PatientRepository</h2>

<img src="Captures/img2.jpg">

<p>La méthode permet de récupérer les patients avec pagination</p>

<h2>Création du contrôleur PatientController</h2>

<p>Le contrôleur PatientController gère les requêtes HTTP et coordonne les interactions entre le modèle (les entités) et la vue (les pages HTML Thymeleaf).</p>

<h2>Création des vues avec Thymeleaf</h2>

<p>Cette vue présente :</p>

<ul>
    <li>Un formulaire de recherche permettant de filtrer les patients par leur nom de famille.</li>
    <li>Une table affichant les informations des patients avec des liens pour supprimer chaque patient.</li>
    <li>La pagination permettant de naviguer entre les pages de résultats.</li>
</ul>

<h1>Résultas</h1>

<h2>Ajout d'un patient</h2>

<img src="Captures/res5.jpg">

<h2>Validation du formulaire</h2>

<img src="Captures/res6.jpg">

<h2>Liste des patients</h2>

<img src="Captures/res1.jpg">

<h2>Recherche</h2>

<img src="Captures/res2.jpg">

<h2>Suppression</h2>

<img src="Captures/res3.jpg">

<h2>Modification</h2>

<img src="Captures/res4.jpg">

 
