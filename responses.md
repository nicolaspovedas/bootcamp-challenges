Ejercicios resueltos parte 1:

<img width="381" alt="Captura de Pantalla 2021-11-10 a la(s) 8 11 29 p  m" src="https://user-images.githubusercontent.com/22968636/141218999-1a62d78e-403c-4138-b58c-a3e603a4d7ae.png">

Ejercicios resueltos parte 2:

<img width="375" alt="Captura de Pantalla 2021-11-10 a la(s) 8 13 17 p  m" src="https://user-images.githubusercontent.com/22968636/141219176-d02c0604-c45a-40e1-8c21-98ed399d9609.png">

RESPUESTAS

1. plate
2. bento
3. #fancy
4. plate apple
5. #fancy pickle
6. .small
7. orange.small
8. bento orange.small
9. plate, bento
10. *
11. plate *
12. plate + apple
13. bento ~ pickle
14. plate > apple
15. orange:first-child
16. plate apple:only-child, plate pickle:only-child
17. .small:last-child
18. plate:nth-child(3)
19. bento:nth-last-child(3)
20. apple:first-of-type
21. plate:nth-of-type(even)
22. plate:nth-of-type(2n+3)
23. plate apple:only-of-type
24. orange:last-of-type, apple:last-of-type
25. bento:empty
26. apple:not(.small)
27. *[for]
28. plate[for]
29. bento[for="Vitaly"]
30. *[for^="Sa"]
31. *[for$="ato"]
32. bento[for*="obb"]





SELECTORES

by html tag: e.g. div

by id: e.g. #long for id="long"

Descendant Selector: e.g. div .long

by class:  e.g. .cards for class="cars"

different selectors (,):  e.g. .cars, .long

Universal selector (*): p*

Adjacent Sibling Selector (+): A + B selecciona 2 de los elementos B que siguen después de A

General Sibling Selector (~):  A ~ B selecciona todos los elementos B que siguen después de A

Child Selector (>): A > B Selecciona todos los elementos B dentro de A

A:first-child: Primer elemento dentro de A

A:only-child: El único elemento dentro de A

A:last-child: El ultimo elemento dentro de A

A:nth-child(#n): el elemento #n dentro de A

A:nth-last-child(#n): Contando desde el último elemento hacia el primero.

B A:first-of-type: Selecciona el primer A dentro de B

A:nth-of-type(#n): Seleccione #n elementos del tipo A. Recibe "even", "odd"

A:nth-of-type(#n+x) con fórmula: Selecciona cada #n eleementos empezando en el x

B A:only-of-type: Selecciona A si solo hay uno dentro de B

B A:last-of-type: Selecciona el último A dentro de B

A:empty: Selecciona los A vacios

:not(A): Selecciona todo lo que NO es A

A[attribute]: Selecciona todos los A que tengan attribute = "lo que sea"

A[attribute="value"]: Selecciona todos los A que tengan atributo y valor igual

A[attribute^="LoQueSea"]: Selecciona los A cuyo attribute EMPIEZA con LoQueSea

A[attribute$="LoQueSea"]: Selecciona los A cuyo attribute TERMINA con LoQueSea

A[attribute*="LoQueSea"]: Selecciona los A cuyo attribute CONTIENE con LoQueSea


ESPECIFIDAD

HTML tag
  Clase
    ID
      El que esté mas abajo
        Important
        
