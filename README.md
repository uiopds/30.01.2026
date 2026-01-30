// 1
let n = -5;
if (n > 0) {
    console.log("positive");
} else if (n < 0) {
    console.log("negative");
} else {
    console.log("zero");
}





// 2
let a = 12, b = 7;
let min = a < b ? a : b;
console.log(min);






// 3 
let n = 15;
if (n % 3 === 0) {
    console.log("yes");
} else {
    console.log("no");
}







// 4 
let N = 7;
let sum = 0;
for (let i = 1; i <= N; i++) {
    sum += i;
}
console.log(sum); // 28





// 5 
for (let i = 1; i <= 15; i++) {
    if (i % 2 !== 0) {
        console.log(i);
    }
}
// 6  
let count = 0;
for (let i = 1; i <= 20; i++) {
    if (i % 2 === 0) {
        count++;
    }
}
console.log(count); // 10






// 7 
let str = "banana";
let count = 0;
for (let i = 0; i < str.length; i++) {
    if (str[i] === 'a') {
        count++;
    }
}
console.log(count); // 3






// 8
let str = "hello";
let reversed = "";
for (let i = str.length - 1; i >= 0; i--) {
    reversed += str[i];
}
console.log(reversed); // "olleh"
// 9 
let num = 4;
for (let i = 1; i <= 10; i++) {
    console.log(`${num} * ${i} = ${num * i}`);
}







// 10 
for (let i = 1; i <= 4; i++) {
    console.log("*".repeat(i));
}






// 11 
let N = 30;
let sum = 0;
for (let i = 1; i <= N; i++) {
    if (i % 3 === 0 || i % 5 === 0) {
        sum += i;
    }
}
console.log(sum); // 225








// 12 
let a = 9, b = 17, c = 17;
let max1 = Math.max(a, b, c);
let min1 = Math.min(a, b, c);
let secondMax = a + b + c - max1 - min1;
console.log(secondMax); // 17 





// 13 
let str = "education";
let vowels = "aeiou";
let count = 0;
for (let i = 0; i < str.length; i++) {
    if (vowels.includes(str[i].toLowerCase())) {
        count++;
    }
}
console.log(count); // 5





// 14 
let str = "level";
let isPalindrome = true;
for (let i = 0; i < Math.floor(str.length / 2); i++) {
    if (str[i] !== str[str.length - 1 - i]) {
        isPalindrome = false;
        break;
    }
}
console.log(isPalindrome ? "yes" : "no"); // yes


// 15 
for (let num = 2; num <= 30; num++) {
    let isPrime = true;
    
    
}
// Результат: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29
