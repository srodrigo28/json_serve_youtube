# Criando Json Api
* Video Construíndo o Projeto
```
https://www.youtube.com/watch?v=1pMeAgzmp9s&list=PL_ummOI2HMvhKHSlIS8_rBtjbh0tUjVqG&index=7
```
```
npm init -y
```

```
npm i nodemon
```

```
npm i json-server
```

script:
```
    "json-server --watch db.json --port 3001"
```

```
{
    "produto":[
        { "id": 1, "desc": "camisa a", "qd": 10, "valor": 50.00},
        { "id": 2, "desc": "camisa b", "qd": 10, "valor": 30.00},
        { "id": 3, "desc": "camisa c", "qd": 10, "valor": 20.00}
    ],
    "cliente":[
        { "id": 1, "cliente": "maria", "tel": "62-9 8592-1100" },
        { "id": 2, "cliente": "eduardo", "tel": "11-9 9988-2030" },
        { "id": 3, "cliente": "mario", "tel": "54-9 7448-8830" },
    ]
}
```