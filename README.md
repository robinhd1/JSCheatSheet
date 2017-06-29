# Javascript, cheat sheet. 

- Les variables [## Les variables]
- Les tableaux
- Conditions : if, else
- Les événements


## Les bases

```javascript 
var string = "Steve"; //Ceci est une chaine de caractère.
var nombre = 4;       //Ceci est un nombre. 
var boolean = true;   //Ceci est un booléen, qui ne peut être qu'égal à vrai ou faux, donc true ou false. 
var monTableau = ["Un", "Deux", "Trois", "Quatre", "Cinq", "Six"]; // Le tableau permet de stocker plusieurs valeur dans une même variable.
var objet = document.getElementbyId("main"); // Un objet peut-être nimporte quel valeur. C'est une structure très utilisée et flexible. 


```


## Les variables 

```javascript 

var age = 20; // Variable basique, peut être utilité en local comme en global. 
let name = "Robin"; // La variable let permet de déclarer une variable qui ne peut être utilité que dans le bloc où elle a été déclaré. 
const sexe = "Homme"; // La variable const ne peut être modifié. Elle peut être appliqué en local comme en global. 
name.length // Affiche la taille de la variable name (5);

```

## Les tableaux 

```javascript 

const monTableau = ["Un", "Deux", "Trois", "Quatre", "Cinq", "Six"];
console.log(monTableau[0]); // Affiche le premier élement du tableau, ici "Un". 
console.log(monTableau[5]); // Affiche le 6 élement du tableau, qui est répértorié à l'index 5, ici "Six". 

monTableau.length; //Permet d'avoir le nombre d'index du tableau. 
monTableau.push("Sept"); // Ajoute "Sept à la fin du tableau. 




```

## Conditions : If, else

```javascript
const num1 = 50;
const num2 = 40;

if (num1 == num2) {
	alert("Egalité");
}else { 
	alert("Différent");
}


```

## Les événements

```javascript

dblclick="";	//Double-cliquer sur l'élément
mouseover="";	//Faire entrer le curseur sur l'élément
mouseout="";	//Faire sortir le curseur de l'élément
mousedown="";	//Appuyer (sans relâcher) sur le bouton gauche de la souris sur l'élément
mouseup="";	//Relâcher le bouton gauche de la souris sur l'élément
mousemove="";	//Faire déplacer le curseur sur l'élément
keydown="";	//Appuyer (sans relâcher) sur une touche de clavier sur l'élément
keyup="";	//Relâcher une touche de clavier sur l'élément
keypress="";	//Frapper (appuyer puis relâcher) une touche de clavier sur l'élément
focus="";	//« Cibler » l'élément
blur="";	//Annuler le « ciblage » de l'élément
change="";	//Changer la valeur d'un élément spécifique aux formulaires (input,checkbox, etc.)
input=""; 	//Taper un caractère dans un champ de texte (son support n'est pas complet sur tous les navigateurs)
select=""; 	//Sélectionner le contenu d'un champ de texte (input,textarea, etc.)


// Spécifique à l'élément <form>
submit; //Envoyer le formulaire
reset; //Réinitialiser le formulaire




```
