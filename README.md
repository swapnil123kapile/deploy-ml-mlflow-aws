<h1>Deploying Models to Production with MLflow and Amazon Sagemaker</h1>

<p>This repo introduces how to prepare you Machine Learning (ML) model for production in AWS Sagemaker with the help of MLflow and AWS Command Line Inteface (AWS CLI). Before start, we should know what is what:
  <ul>
    <li><b>Mlflow</b> - an open source platform for the ML lifecycle.</li>
    <li><b>AWS CLI</b> - is an unified tool to manage your Amazon Web Services (AWS) services.</li>
  </ul>
With this repo you can follow the provided steps on your local machine and AWS account. All steps will be explained clearly with screens and real example.
</p>

<h2>Setup</h2>
<p>For this tutorial you will need:
  <ul>
    <li>AWS Account.</li>
    <li>Docker installed on your local machine.</li>
    <li>Python <b>3.6</b> (or higher) with <code>mlflow>=1.0.0</code> installed.</li>
    <li>Anaconda software to create conda virtual environment.</li>
  </ul>
 Next, I will demonstrate how to install <i>mlflow</i> to your dedicated virtual environment. For this I will use Mac OS, but you can do the same steps on both Windows and Mac OS.
 
 <p><h3>Step 1. Prepare you Python Virtual environment</h3>
 With this step we will create dedicated virtual environment to perform the whole example in this repo. Do the following steps.
 <ul>
  <li>Create a new conda virtual environment in you working directory with the following command in your terminal:<br><code>conda create --name deploy_ml python=3.6</code><br>With this command you will create a new conda based virtual environment on your local machine.</li>
  <li>Once your virtual environment is sucessfully create, you can easily to activate it with the following command:<br><code>conda activate deploy_ml</code><br>At this moment we are having an almost empty virtual environment which is ready to be filled with new dependencies.</li>
 </ul>
 </p>
 
 <p><h3>Step 2. Install dependencies in you virtual environment</h3></p>
<ul>
  <li>Install <i>mlflow</i> package into our virtual environment with the following command:<br><code>pip install mlflow</code>.</li>
</ul>
</p>
