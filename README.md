# oslash_test

## College Stationary Shop

### Context

College stationery shop is running its annual clearance sale. It is offering steep discounts on a few of the products for this exclusive sale event. They need your help in coming up with a bill calculator.

### Products

There are 2 different categories of products. The cost and discount per products are different. Following products are available for the sale at the shop.

Example-

| Product  | Category | Original Price in Rupees | Discount for the sale |
| ------------- | ------------- | ------------- | ------------- |
| TSHIRT  | Clothing  | 1000 | 10% |
| JACKET  | Clothing  | 2000 | 5% |
| CAP | Clothing  | 500 | 20% |
| NOTEBOOK | Stationary  | 200 | 20% |
| PENS | Stationary  | 300 | 10% |
| MARKERS | Stationary  | 500 | 5% |

### Input Sample 1
>ADD_ITEM TSHIRT 2
<br>
>ADD_ITEM NOTEBOOK 1
<br>
>PRINT_BILL

### Output Sample 1
>ITEM_ADDED
<br>
>ITEM_ADDED
<br>
>TOTAL_DISCOUNT 240.00
<br>
>TOTAL_AMOUNT_TO_PAY 2156.00
