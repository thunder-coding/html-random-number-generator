# js-random
This website generates random numbers

# demo
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width,initial-scale=1.p">
  		
		<script src="Random.js">
  	
  		</script>
			<div align=center>
				<button onclick="ShowRandomNumber()" style="margin-top:50%">RANDOM</button>
		<br><br>	<input id="number" value="0" type="number" onchange="check_value(this.value)" oninput="check_value(this.value)">
				<output id ="a"></output>
		<br>		<output id ="x" style="display:none; color:red; font-size:33%;">Number should be in the legal range i.e. 0-999</output>
			</div>
