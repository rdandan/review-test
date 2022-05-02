# Introduction of Review Mirror

ReviewMirror is a website tool to help users to gain insightful information from reviews as well as to detect product on e-commerce sites which has fake reviews.

We create a review mirror website solution that will use a machine learning model to identify products with deceptive reviews, provide summary points of reviews, and provide other important insights from reviews.

## Link to our website

https://www.reviewmirror.ga

## Current Features

1. Analysing Reviews: you can copy and paste a review from amazon or other platforms to analyse review function and the website will show whether this review is generated by computer or written by human
2. Information: you can get more knowledge about how to identify fake reviews at information page
3. Offer a summary of product reviews via a wordcloud when the user enters the product's link from the Amazon.AU website. Additionally, we provide a wordcloud that displays the most frequently used positive and negative words in product reviews, giving users a sense of the product's pros and cons based on consumer feedback. Moreover, our Ml model will filter out any possible phoney reviews for the provided product link and deliver a recalculated star rating after the bogus reviews are filtered out.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.


This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

# Back end lambda function in aws

[analysis_handler.py](https://github.com/XuezhengLiu/ReviewMirror/blob/master/Python/analysis_handler.py)
[db_handler.py](https://github.com/XuezhengLiu/ReviewMirror/blob/master/Python/db_handler.py)

# python dependencies

[requirements.txt](https://github.com/XuezhengLiu/ReviewMirror/blob/master/Python/requirements.txt)

You can find the requirements.txt in the python folder that helps you install the packages
