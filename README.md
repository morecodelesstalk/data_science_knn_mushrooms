# K-Nearest-Neighbors - Data Science

### <center>Classificação de cogumelo venenoso</center>
![](https://kennettmushrooms.com/wp-content/uploads/2017/05/fungi-funnys-570x285.jpg)

### Sobre o conjunto de dados:
A primeira coluna é um classificador
0. Classe: comestível e, venenoso p

O restante das colunas é
1. cap-shape:
   - bell = b
   - conical = c
   - convex = x
   - flat = f
   - knobbed = k
   - sunken = s 
2. cap-surface:
   - fibrous = f
   - grooves = g
   - scaly = y
   - smooth = s 
3. cap-color:
   - brown = n
   - buff = b
   - cinnamon = c
   - gray = g
   - green = r
   - pink = p
   - purple = u
   - red = e
   - white = w
   - yellow = y 
4. bruises?:
   - bruises = t
   - no = f 
5. odor:
    - almond = a
    - anise = l
    - creosote = c
    - fishy = y
    - foul = f
    - musty = m
    - none = n
    - pungent = p
    - spicy = s

### Abordagem:

1. Variáveis X e Y separadas
2. Use o codificador de etiquetas para substituir os dados de texto
3. Projete um codificador hot multicolumn one
4. Prever resultados
5. Revise o K ideal
6. Encontrar características do cogumelo venenoso

### Notas:

1. Existem várias colunas de variáveis categóricas. Precisamos evitar a variável dummy Trap
2. Encontre uma maneira de renomear as colunas após a conclusão de uma operação de codificador quente
