# Apache Cordova android plugin payhere.lk payment gateway


### JavaScript
```javascript
        window.payhereClient.checkout( {
	    merchantId: "<PAYHERE_SANDBOX_MERCHANT_ID>",
	    merchantSecret: "<PAYHERE_SANDBOX_MERCHANT_SECRET>",
            amount: 1180.50, // Amount which the customer should pay
            currency: "LKR",
            orderId: "123",
            itemsDescription: "Desc",
            custom1: "",
            custom2: "",
            customer: {
              firstName: "Dan",
              lastName: "Jay",
              email: "shandanjay@gmail.com",
              phone: "0715753168"
            },
            billing: {
              address: "5A",
              city: "Colombo",
              country: "Sri Lanka"
            },
            shipping: {
              address: "Park Avenue", //shipping
              city: "5A", // shipping
              country: "" //shipping
            }
            //Item(null, "Door bell wireless", 1));

          },
          function (param) {
            console.log(param);
          },
          function (param) {
            console.log(param);
          }
        );
```


