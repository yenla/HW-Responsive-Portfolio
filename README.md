# HW-Responsive-Portfolio

Live Link 

https://yenla.github.io/HW-Responsive-Portfolio/index.html

Summary

This homework assignment require us to implement media query into our css to make our website responsive. 

For example:

@media screen and (max-width: 640px) {
	
	body {
		width:50%;
		height:100%;
		background: url(../images/redox_01_@2X.png) 0 0;
		background-position: center; 
		/*background-size: 50% 50%;
    	background-repeat: no-repeat;*/
	}
	header { 
		width: 106%;
		height: 105px;
		background-color: #fff;
		/*height: 65px; */

	}
	.author-name {
		width: 88%;
		left: 0;
		text-align:center;
	}

	header h1 {
		padding: 20px;
    	font-size: 25px;
	}
}
