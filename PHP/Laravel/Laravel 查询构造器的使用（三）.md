查询构造器中的构造函数

```
	//聚合函数
    public function query5()
    {
        $num = DB::table('student')->count();
        var_dump($num);

        $max = DB::table('student')->max('age');
        var_dump($max);

        $min = DB::table('student')->min('age');
        var_dump($min);

        $avg = DB::table('student')->avg('age');
        var_dump($avg);

        $sum = DB::table('student')->sum('age');
        var_dump($sum);
    }
```