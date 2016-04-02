<html>
<head>
<title>my project</title>
<script src="/bower_components/platform/platform.js"></script>
<link rel="import" href="/bower_components/paper-elements/paper-elements.html">
<link rel="import" href="/bower_components/paper-input/paper-input.html">
<link rel="import" href="/bower_components/custom/hello-world.html">
</head> 
<body>
<form action="www.google.com" method="get">
<h1>info</h1>
<fieldset>
<fieldset>
<legend>personal</legend>
NAME:<paper-input label="text input"></paper-input>  
password:<paper-input label="this input requires some text" required auto-validate error-message="needs some text!"></paper-input>
gender:<br><paper-checkbox>male</paper-checkbox>
       <paper-checkbox>female</paper-checkbox>
</fieldset>
<fieldset>
<legend>qualification</legend>
subject:

<input type="submit" value="sumbit" name="submit">
</fieldset>
</form>
<paper-button raised>test</paper-button> 
<hello-world></hello-world> 
</body>
</html>

