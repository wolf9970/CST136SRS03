# CST136SRS03

Stone Template Pirates

Student Name: John Kaye

Issues: not sure if std::map builds during compile or run time. Had trouble expanding param pack; ended up loading params
        into a vector. There is probably a better way to do it.

Notes: attempted to make my template as generic as possible by using a variadic function template with a parameter pack.
       
       

----

Project Name: StoneMoney

Purpose:

- Learn to use templates.
- Understand the difference between compile-time and run-time code. 

In this project you will leave the shores of New Zealand and sail NW to the island of [Yap](https://en.wikipedia.org/wiki/Yap). 

The island of Yap has treasure all over the island, and it isn't even hidden. The money isn't in the form of gold, but in the form of large [Rai stones](https://en.wikipedia.org/wiki/Rai_stones). 

You could just walk up and take the money, except you don't know if it is worth the effort. 

To figure this out, you need to write templates to convert the value of local currency to other currencies. 

You need to write templates to convert between currencies. Your goal is to generate **NO** code. Ideally this means everything is calculated by the compiler.  

Here is a conversion table you can use for your software:  

| Country          | Code | Value |
| ---------------- | ---- | ----- |
| United States    | US   | 1.0   |
| Australia        | AU   | 0.76  |
| New Zealand      | NZ   | 0.71  |
| Fiji             | FJ   | 0.49  |
| Tonga            | TO   | 0.45  | 
| Papua New Guinea | PG   | 0.31  |
| Solomon Islands  | SB   | 0.13  | 

see: https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2 for a list of 2 letter country codes
