Hey! This projectwas built as a part of Hack Club Half Life. It was originally intended to be a tamagotchi toy, but i instead turned it into a short, pokemon style game. 

You start out with the character blobb (who is essentially a blob) and once you win a battle, the game lets you evolve it into a Blocky  (who is made of striaght lines) OR a spiky (who is spiky).
Winning further battles lets you evolve your character, and including the initial stage, there are 3 evolutions of each character.

Battles have also been changed from a your character vs. other character battle to a your character vs. AI Tic-tac-toe game.

You control the Tic-Tac-toe game by tilting the entire pcb. once you're in the right position, click the top switch to lock it in. The AI then does its turn, and the battle continues like this.

Visit https://wokwi.com/projects/477641998977817601 to test it out virtually, meaning you don't even need the pcb! To do this, click the green play button in the  top left of the hardware panel. You can then just left click the accelerometer (which is the blue chip near the very top) and change the rotation bars to "Tilt" the accelerometer. SW1 is the top switch, and SW2 is the bottom switch.

The online simulation should look like this:
<img width="908" height="880" alt="image" src="https://github.com/user-attachments/assets/4232a93d-fa27-49d2-8c53-b1da97daec3f" />


Here's a 3D render of the pcb!
<img width="1295" height="1058" alt="image" src="https://github.com/user-attachments/assets/c6462e2b-cba4-433c-93b7-7a4508856ed9" />

And here's a BOM

| Item | Qty | Supplier | Cost/item | Total Cost | Link |
|---|---:|---|---:|---:|---|
| Header Pins | 1 | TLZWLA Official Store | $1.39 | $1.39 | [Link](https://www.aliexpress.us/item/3256805072379643.html?spm=a2g0o.cart.0.0.106c38daIS6h4V&mp=1&pdp_npi=6%40dis%21USD%21USD+1.39%21USD+1.39%21%21USD+1.39%21%21%21%402101ea8f17928801450344904e09f1%2112000032390031595%21ct%21US%218282744365%21%211%210%21&_gl=1*1yuvcyf*_gcl_au*Mjg4MjIyMTY4LjE3OTE3NjI1MDg.*_ga*MTAzODc3Mzk3MS4xNzkxNzc1MzQ2*_ga_VED1YSGNC7*czE3OTI4Nzk4NjYkbzQkZzEkdDE3OTI4ODAxNDkkajMkbDAkaDA.&gatewayAdapt=glo2usa) |
| DHT11 | 1 | Lucky Electonics Components Store | $1.66 | $1.66 | [Link](https://www.aliexpress.us/item/3256808602611303.html?spm=a2g0o.cart.0.0.106c38daIS6h4V&mp=1&pdp_npi=6%40dis%21USD%21USD+1.66%21USD+1.66%21%21USD+1.66%21%21%21%402101ea8f17928801450344904e09f1%2112000046667765928%21ct%21US%218282744365%21%211%210%21&_gl=1*66ti7f*_gcl_au*Mjg4MjIyMTY4LjE3OTE3NjI1MDg.*_ga*MTAzODc3Mzk3MS4xNzkxNzc1MzQ2*_ga_VED1YSGNC7*czE3OTI4Nzk4NjYkbzQkZzEkdDE3OTI4ODAyMTIkajM1JGwwJGgw&gatewayAdapt=glo2usa) |
| MPU6050 | 1 | Nextronics Store | $1.09 | $1.09 | [Link](https://www.aliexpress.us/item/3256812536361672.html?spm=a2g0o.cart.0.0.106c38daIS6h4V&mp=1&pdp_npi=6%40dis%21USD%21USD+3.88%21USD+1.09%21%21USD+1.09%21%21%21%402101ea8f17928801450344904e09f1%2112000059167286842%21ct%21US%218282744365%21%211%210%21&_gl=1*1zokem*_gcl_au*Mjg4MjIyMTY4LjE3OTE3NjI1MDg.*_ga*MTAzODc3Mzk3MS4xNzkxNzc1MzQ2*_ga_VED1YSGNC7*czE3OTI4Nzk4NjYkbzQkZzEkdDE3OTI4ODAyMTYkajMxJGwwJGgw&gatewayAdapt=glo2usa) |
| Keycaps | 1 | SZ Electronic Store | $3.76 | $3.76 | [Link](https://www.aliexpress.us/item/3256808640925468.html?spm=a2g0o.cart.0.0.106c38daIS6h4V&mp=1&pdp_npi=6%40dis%21USD%21USD+3.76%21USD+3.76%21%21USD+3.76%21%21%21%402101ea8f17928801450344904e09f1%2112000046843776637%21ct%21US%218282744365%21%211%210%21&_gl=1*11iiwlw*_gcl_au*Mjg4MjIyMTY4LjE3OTE3NjI1MDg.*_ga*MTAzODc3Mzk3MS4xNzkxNzc1MzQ2*_ga_VED1YSGNC7*czE3OTI4Nzk4NjYkbzQkZzEkdDE3OTI4ODAyNjkkajYwJGwwJGgw&gatewayAdapt=glo2usa) |
| Resistors | 1 | FANGXIN Store | $6.75 | $6.75 | [Link](https://www.aliexpress.us/item/3256811714023367.html?spm=a2g0o.cart.0.0.106c38daIS6h4V&mp=1&pdp_npi=6%40dis%21USD%21USD%2015.00%21USD%206.75%21%21USD%206.75%21%21%21%402101ea8f17928801450344904e09f1%2112000056933163749%21ct%21US%218282744365%21%211%210%21&_gl=1*9nhjgb*_gcl_au*Mjg4MjIyMTY4LjE3OTE3NjI1MDg.*_ga*MTAzODc3Mzk3MS4xNzkxNzc1MzQ2*_ga_VED1YSGNC7*czE3OTI4Nzk4NjYkbzQkZzEkdDE3OTI4ODAzNjEkajYwJGwwJGgw&gatewayAdapt=glo2usa&_randl_shipto=US) |
| OLED | 1 | AOKIN | $0.33 | $0.33 | [Link](https://github.com/user-attachments/assets/14cdffc6-8f83-4813-89f4-dde2b5d74e93) |
| Estimated total shipping | 1 |  |  | $0.00 |  |
