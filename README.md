

<!DOCTYPE html>
<html>
<head>
	<title>Login And Registration Form Design</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="login-page">
		<div class="form">
			<form class="register-form">
				<input type="text" placeholder="user name"/>
				<input type="text" placeholder="password"/>
				<input type="text" placeholder="email-id"/>
				<button>Create</button>
				<p class="message">Already Registered?<a href="#">Login</a>
				</p>
			</form>
			<form class="login-form">
				<input type="text"placeholder="user name"/>
				<input type="text"placeholder="password"/>
				<button>login</button>
				<p class="message">Not Registered? <a href="#">Register</a></p>
				<script src='https://code.jquery.com/jquery-3.2.1.min.js'>
				</script>
				<script>
					$('.message a').click(function(){$('form').animate({height: "toggle",opacity: "toggle"},"slow");});
				</script>






			</form>
		</div>
	</div>
</body>
</html>












