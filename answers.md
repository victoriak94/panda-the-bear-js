
ART 1

1.
document.getElementsByClassName("profile-image")[0].setAttribute("src", "https://savethee.files.wordpress.com/2012/06/pandafix1.jpg")

2.
document.querySelectorAll('[title="Man Walking on Ice"]')[0].setAttribute("src", "http://www.edinphoto.org.uk/0_my_p_sk/0_my_photographs_sky_-_cramond_island.jpg");

3.
document.getElementsByTagName('h1')[0].innerText= "Victoria";

4.
document.querySelector(".info-title").innerHTML=('Experience')

5.
document.getElementsByTagName('body')[0].style.backgroundColor = 'gold'

6.
for (i in document.getElementsByClassName("highlight")) { document.getElementsByClassName("highlight")[i].style.color='yellow' }

7.
document.getElementsByTagName('h1')[0].style.fontFamily = 'monospace'

8.
for (i in document.getElementsByClassName("action-icon-bg")) { document.getElementsByClassName("action-icon-bg")[i].style.backgroundColor="#666666" }

9.
document.getElementById("name").setAttribute("placeholder", "Identify yourself")

10.
document.getElementById("message").setAttribute("placeholder", "state your business")

11.
document.getElementById("name").setAttribute("value", "your nemesis")

12.
document.getElementById("email").setAttribute("value", "koalathebear@gmail.com")

13.
document.getElementById("submit").setAttribute("value", "En garde!")

14.
document.getElementById("submit").setAttribute("disabled", true)

15.
for (i in document.getElementsByClassName("bio-info-value")) { document.getElementsByClassName("bio-info-value")[i].innerHTML="classified" }

PART 2

1.
document.getElementsByClassName('portfolio-container')[0].appendChild(document.querySelectorAll('[title="Pikachu"]')[0].cloneNode())

2.
for (let i = 0 ; i < 10 ; i++) { document.getElementsByClassName('portfolio-container')[0].appendChild(document.querySelectorAll('[title="Pikachu"]')[0].cloneNode()) }

3.
const listItem = document.createElement('li'); const leftSpan = document.createElement('span'); const rightSpan = document.createElement('span'); var lastUpdated = document.createTextNode('Page last updated on'); var date = document.createTextNode(new Date());

listItem.className = "bio-info-item"; leftSpan.className = "bio-info-title"; leftSpan.className = "bio-info-value";

rightSpan.appendChild(date); leftSpan.appendChild(lastUpdated); listItem.appendChild(leftSpan); listItem.appendChild(rightSpan);

document.getElementsByClassName('bio-info')[0].appendChild(listItem)
