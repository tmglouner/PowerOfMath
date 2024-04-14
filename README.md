# PowerOfMath
In this web application(hosted on AWS Amplify) you can enter a base number and an exponent:<br><br>

<img width="560" alt="PowerOfMathUI" src="https://github.com/tmglouner/PowerOfMath/assets/166273662/a8a2989c-0285-421e-a7de-7c36e3573a20"> <br><br>

After clicking "CALCULATE" a POST API method is triggered utilizing Amazon API Gateway and<br> 
an AWS Lambda function(with permissions configured in AWS Identity and Access Manager) in order<br> 
to calculate the mathmatical answer and return it to the user:<br><br>

<img width="392" alt="PowerOfMathResponse" src="https://github.com/tmglouner/PowerOfMath/assets/166273662/f3a6dbc9-abd9-4fe0-80a1-ea97b7b64ecb"> <br><br>

Additionally, That mathmatical answer is stored in an Amazon DynamoDB database: <br><br>

<img width="667" alt="PowerOfMathDB" src="https://github.com/tmglouner/PowerOfMath/assets/166273662/24c61bed-8c31-4715-9059-1b58d4e80df3"> <br><br>

Try it out by clicking the link below:<br>
https://main.d5v1fbaye82t2.amplifyapp.com/



