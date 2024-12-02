![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

# Order Book
Basic limit order book ( LOB ) implementation in Typescript.

## What is an limit order book ( LOB ) ?

Limit order book ( LOB ) is an record of all buy and sell limit orders being currently set in the market. It essentially showcases all supply and demand waiting to be filled using aggressive/market orders. Aside from that, limit order book also showcases ask and bid quotes currently available for buy/sell aggressive order fill.

![image](https://github.com/user-attachments/assets/9dfa9d04-d3bf-4f1f-ac5e-7094f454cefe)

## What's developed

- Custom sorted map type ( for performance )
- Order book
  - Feature for limit order setup
  - Feature for market order setup 
  - Feature for directly getting the book ( with volume )
  - Feature for getting current best bid/ask

## Resources

[1. Investopedia](https://www.investopedia.com/terms/l/limitorderbook.asp)
[2. Wikipedia](https://en.wikipedia.org/wiki/Central_limit_order_book)
[3. UCLA](https://www.math.ucla.edu/~mason/papers/gould-qf-final.pdf)
