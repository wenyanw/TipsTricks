# TipsTricks
tips for C#, Js,etc
1. Email validation with Regex:
var isEmailValid = Regex.IsMatch(emailAddress, @"\A(?:[a-z0-9!#$%&'*+/=?^_`{|}~-]+(?:\.[a-z0-9!#$%&'*+/=?^_`{|}~-]+)*@(?:[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\.)+[a-z0-9](?:[a-z0-9-]*[a-z0-9])?)\Z", RegexOptions.IgnoreCase);    

2. Debug angular json object, apply "{{object | json}}" will display json format data without using dev12 tool
3. unique filter provided by Ben Lesh
  http://stackoverflow.com/questions/20222555/angularjs-remove-duplicate-elements-in-ng-repeat

