let a=Math.floor(Math.random()*100)
let x=0
let c=0
while(x==0)
  {
    let b=prompt("enter ur number")
    b=Number.parseInt(b)
    c++
    if(b==a)
    {
      console.log("congo u guessed in  "+c+"  chances")
      x++
    }
    if(b>a)
      console.log("ur guess is greater")
    if(b<a)
      console.log("ur guess is lesser")
  }
let d=100-c
console.log("ur final score is  "+d)
