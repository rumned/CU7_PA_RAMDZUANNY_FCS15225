Prediction of 0 : Customer Stays
Prediction 1: Customer Churns
bad request: 400
Failed to predict data '   avg_hours_week      plan main_device  ...  monthly_fee_rm  payment_method contract
0             3.0  Standard          TV 
Error: Model is missing inputs ['support_calls'].

The status code 400 tells us that the request is a client side error, because our request is incomplete (missing inputs support_calls, as per error message)