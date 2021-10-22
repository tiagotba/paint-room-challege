# paint-room-challege
## Descrição do Projeto
<p align="left">This microservice is responsible for calculating the amount of paint cans to paint a 4-wall room.</p>
<h3> Installation</h3>
<p align="left">yarn is used to install and execute the micro-service Example : yarn</p>

<h3> Execution</h3>

<p align="left">Make sure you have created and started all instances of the required services. Otherwise, you can simply run the tests, this will force you to create all of them</p>

<b>Example:</b> yarn start:dev

<h3> Test</h3>

<b>Example:</b> yarn test

<h1> Documentation</h1> 

<b>Swagger</b> URL.: http://localhost:3000/api-docs

<h1> Route</h1>

<b>METHOD.:</b> POST <br/>
<b>URL.:</b> http://localhost:3000/paint

<h1> INPUT example - General all fields</h1>

{
  "wall": [
    {
      "heigth": 2,
      "width": 8
    },
    {
      "heigth": 2,
      "width": 8
    },
    {
      "heigth": 2,
      "width": 8,
      "door": 1
    },
    {
      "heigth": 2,
      "width": 8,
      "window": 1
    }
  ]
}
