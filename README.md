### A aplicação

Esta api compõe um projeto desenvolvido durante a semana oministack, realizado pela RocketSeat. Nela, desenvolvemos uma aplicação base para compartilhamento de escritórios.
O projeto se compões de :
- Backend contruido com NodeJS,MongoDB e express.js;
- WebApp de administração contruido em ReactJS;
- Mobile contruido com React-Native e Socket.Io;

# Construção da Api

[![AirCnc_logo](https://i.imgur.com/vqdhqGZ.png "AirCnc_logo")](# "AirCnc_logo")

A api, que utiliza express e mongoose para se conectar ao MongoDB, foi feita totalmente em NodeJS, com recursos de Socket.Io para comunicação em tempo real com mobile e webapp.

Como funciona
=============

A aplicação recebe as solicitações via HttpRequest, em diferentes metódos ( Post, Get, Put);
A partir da requisição, a mesma será tratada e a api irá consultar o banco de dados, manipulando e retornando todas as informações necessárias para o mobile e para a webapp.
