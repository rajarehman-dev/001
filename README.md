# 001

Day : 02-02-2026
{
    Setup Github : rajarehman-dev
    Create a Repository
    - git clone URL
    - git add .
    - git commit -m "message"
    - git status
    - git push origin main

    for all files put "use strict"; on the very first line. This forces the engine to use newer syntax.
    
    Variables are const and let , also var ( which is recomended not to use )
    const represents constant values , let gives variables ( in JS unlike C++ , There is no need for manually declairing variable type )
    
    use typeof VN to check type of any variable on runtime
    any variable can be converted into any other variable , However the value might get lost if it is improper
    For example :-
    ( 1 )
    let x = "911"
    x = Number(x)
    console.log(typeof x)
    console.log(x)
    Output = number
    ( 2 )
    let x = "911pkg"
    x = Number(x)
    console.log(typeof x)
    Output = NaN
    console.log(x)
    [ Here the NaN represents "Not a Number" , the value 911pkg is lost and the variable is useless ]
    
    parseInt() is a built in function that can be used to pull out numerical values in a variable

    ++X increments the value before usage
    X++ increments the value after usage

    in javascript there are 2 types of comparison operators when it comes to equality "==" which works as expected
    but there is also "===" which does not allow type conversions and only works if both varibales are of smae the type
    console.log('7'==7) , Output = True
    console.log('7'===7) , Output = False
    console.log(7===7) , Output = True

    Primitive Data Types : a copy is given when these are fetched from memory
    Number , String , Boolean , Symbol , BigInt , undefined , null

    Non-Primitive Data Types : a refrence is given when these are fetched from memory
    Arrays , Objects and Functions

    arx[3] = {11,19,32}
    let obj = {
        name : "ABC"
        age : 20
        isTall : True
    }
    const Function1 = function(){ console.log("Hello World") }
}

Day : 02-02-2026
{
    Stack and heap are data types used mainly by the memory management module of a language , Unlike C++ there is a garbage collector that
    makes the life of a developer significantly easier , However the mechanish of a stack and heap are fun to know
    Stack : When the "what" and "How much" is known , Heap : When the memory requirment changes on runtime

    

}