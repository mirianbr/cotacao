# USD-BRL exchange rates calculator

Nano-project exploring ways of extracting USD-BRL exchange rates to calculate income taxes for money received from abroad.

## About

Brazil has a very interesting way to tax money received from abroad. You have to convert the amount received to US dollars (regardless of the currency the money you received is in), and then you can convert it to BRL using the exchange rate for the last business day of the first fortnight of the month prior to the payment month. 

The USD-BRL exchange rate is a challenge in itself: one cannot simply [Yahoo finance it](https://finance.yahoo.com/quote/USDBRL=X/). The exchange rate needs to use something called "Ptax Closing Rate", which is [the average of the rates Bid and Offer of the bulletins of the day](https://www.bcb.gov.br/en/financialstability/quotations).

See [this FAQ by the Brazil government](https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/perguntas-frequentes/declaracoes/dirpf/pr-irpf-2021-v-1-0-2021-02-25.pdf)  (Portuguese only) to learn more. The conversion to BRL topic is under the "156" title, page 81.

## How to

* [Using Google sheets](https://docs.google.com/spreadsheets/d/1GNjj3T8Xui7oRoQkrKOgb3Jx-1ptR16IjtY-gX_73gg/edit#gid=0) ([pt-BR](https://docs.google.com/spreadsheets/d/1ijILRdL32EJjuhzPYAs3rjAdj83viPhWnZO5BG2Wu_Y/edit?usp=sharing))
* [Using Microsoft Excel](Exchange_rates-PQ-en.xlsx) ([pt-BR](Exchange_rates-PQ-ptBR.xlsx)
