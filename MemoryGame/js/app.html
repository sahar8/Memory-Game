// save all image in cards 
const cards = document.querySelectorAll('.cards');
let move = document.querySelector('.moves');
let stars = document.querySelector('.stars');
let times = document.querySelector('#timer');
let board = document.querySelector('.Board_game');


let fliped = false;
let freeze = false;
let firstClick = true; // for timer if true the timer is run 
let match = 0;
let Moves = 0;
let time = 0;
let starNum;
let Fcard, Scard;

const imageCon = document.querySelectorAll('.back_face');


// store all Cards then sent to shuffle to random it
let shuffledCards = shuffle([...cards]);
console.log(shuffledCards)

board.innerHTML = '';
for(let card of shuffledCards) {
	board.appendChild(card);
}



/* function to count the number of flip the cards ,
if the flip less than 21 the user will be take 3 stars , 
if the flip between 20 and 26 will ba take 2 stars else will be take 1 stars */
function movesCo (move) {
	console.log(move)
		if ( move >= 25) {
stars.innerHTML = '⋆';
     }
	else if ( move >= 20) {
stars.innerHTML = '⋆⋆';
starNum = stars;
	}
}


let timee;
function timer() {
	var timer = setInterval ( function() {
	time++;
	times.innerHTML = 'timer : ' + (time) + ' seconds' ;
}, 1000);
}


// this function will be start if user click the cards ,
function flip(event) {

	if (freeze) 
		return;
	if (this === Fcard) return;
	if (firstClick) {
		firstClick = false;
		timer();
	}	
	Moves++;
	// increase the counter of moves after each click on the cards 
	move.innerHTML = (Moves);
	// to put stars based on number of moves
	movesCo(Moves);
	this.classList.add('flip');
/* if the card not flip , if clicked will be add flip class on it */

if (!fliped) {
	console.log(this)
	// first click 
	fliped = true;
	Fcard = this;
}
else {
	fliped = false;
	Scard = this;


  if (Fcard.getAttribute('data-image') === Scard.getAttribute('data-image')) {
  	console.log('match')
		// it is match ?
		Fcard.removeEventListener ('click', flip);
		Scard.removeEventListener ('click', flip);
		match++;

		 if ( match == 8) {
			// if user win the timer will be stopped by continous = false
			continuous = false;
			let msg = `Congratulations you are won \n in : ${time} Seconds , and ${starNum.innerHTML} Srats. 
			\n if you want to play agin press OK then click Restart Button`;
			alert(msg);
		 }
   }
 else {
 	    freeze = true;
		// not match 
		setTimeout (() =>
		{
			Fcard.classList.remove ('flip');
			Scard.classList.remove ('flip');
		freeze = false; }, 1000);
      }  
}
}

cards.forEach (card => card.addEventListener('click', flip));




// Shuffle function from http://stackoverflow.com/a/2450976
function shuffle(array) {
    var currentIndex = array.length, temporaryValue, randomIndex;
    while (currentIndex !== 0) {
        randomIndex = Math.floor(Math.random() * currentIndex);
        currentIndex -= 1;
        temporaryValue = array[currentIndex];
        array[currentIndex] = array[randomIndex];
        array[randomIndex] = temporaryValue;
    }

    return array;
}

// to restart game
function restart () {
	location.reload();
}