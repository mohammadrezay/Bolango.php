# Bolango.php
https://quera.org/problemset/3430?tab=description
<?php
$n = (string)readline("Enter a word: ");
$w = str_split($n);
for($i = 0; $i <= strlen($n); $i++){
	$m = substr($n, $i, strlen($n));
	$r = str_repeat($w[$i], $i);
	echo $r . $m . PHP_EOL;
}
