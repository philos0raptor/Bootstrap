# Bootstrap
Basic Bootstrap practice 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title></title>
    <meta charset="UTF-8">
    <title> Movie Review sites </title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
    <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
</head>
<div class="container">
<body>
<h4>I am practicing with tables</h4>
<p>Basic Table</p>
<table class="table">
    <thead>
    <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>email</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>Jim</td>
        <td>Johnson</td>
        <td>jim.johnson@yahoo.com</td>
    </tr>
    <tr>
        <td>Jill</td>
        <td>Jacobs</td>
        <td>Jill.jacobs@yahoo.com</td>
    </tr>
    <tr>
        <td>John</td>
        <td>Joseph</td>
        <td>john.joseph@yahoo.com</td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    </tbody>
</table>
<br >
<p>Table with striped rows</p>

<table class="table table-striped">
    <thead>
    <tr>
        <th>Frist Name</th>
        <th>Last Name</th>
        <th>email</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>Jim</td>
        <td>Johnson</td>
        <td>jim.johnson@yahoo.com</td>
    </tr>
    <tr>
        <td>Jill</td>
        <td>Jacobs</td>
        <td>Jill.jacobs@yahoo.com</td>
    </tr>
    <tr>
        <td>John</td>
        <td>Joseph</td>
        <td>john.joseph@yahoo.com</td>
    </tr>
    </tbody>
</table>
<br >
<p>Table with borders</p>
<table class="table table-bordered">
    <thead>
    <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>email</th>
    </tr>
    </thead>
    <tr>
        <td>Jim</td>
        <td>Johnson</td>
        <td>jim.johnson@yahoo.com</td>
    </tr>
    <tr>
        <td>Jill</td>
        <td>Jacobs</td>
        <td>Jill.jacobs@yahoo.com</td>
    </tr>
    <tr>
        <td>John</td>
        <td>Joseph</td>
        <td>john.joseph@yahoo.com</td>
    </tr>
</table>
<br >
<p>Using contextual classes with tables</p>
<table class="table">
    <thead>
    <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>email</th>
    </tr>
    </thead>
    <tr class="success">
        <td>Jim</td>
        <td>Johnson</td>
        <td>jim.johnson@yahoo.com</td>
    </tr>
    <tr class="info">
        <td>Jill</td>
        <td>Jacobs</td>
        <td>Jill.jacobs@yahoo.com</td>
    </tr>
    <tr class="danger">
        <td>John</td>
        <td>Joseph</td>
        <td>john.joseph@yahoo.com</td>
    </tr>
</table>
</body>
</div>
</html>
