let container = document.getElementById("container");
let currentPage = 0;

function showPage(){
container.style.transform = `translateY(-${currentPage * 100}vh)`;
}

function nextPage(){
currentPage++;
showPage();
}

function prevPage(){
currentPage--;
showPage();
}
