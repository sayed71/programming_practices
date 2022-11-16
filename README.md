## Problem-1: Write Program for Output
1 <br>
23 <br>
456 <br>
78910 <br>

## Problem-2: Write Program for Output
1 <br>
12 <br>
123 <br>
1234 <br>
12345 <br>
123456 <br>
1234567 <br>
12345678 <br>
123456789 <br>

```
<?php
	$count=1;

	for($i=1; $i<=10; $i++)
	{
		for($j=1; $j<$count; $j++)
		{
			echo $j;
		}

		$count=$count+1;

		echo "<br>";
	}

?>
```



