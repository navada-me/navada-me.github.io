function daily() {
  var today = new Date();
  
  if (today.getMonth() < 10) {
    var mon = "0"+today.getMonth();
  }else{
  var mon = today.getMonth();
  }
  
  if(today.getDate() < 10 ){
    var date = "0"+today.getDate();
  }else{
  var date = today.getDate();
  }
  document.getElementById('linkto').innerHTML=date+"/"+mon+"/"+today.getFullYear();
  
  document.getElementById('linkto').href = "https://epaper.thehindu.com/pdf/"+today.getFullYear()+"/"+mon+"/"+date+"/"+today.getFullYear()+mon+date+"3A.zip";
}
