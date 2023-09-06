### Встроенная функция new  

Еще одним способом создания переменной является применение встроенной функции new.
Выражение new(T) создает неименованную переменную типа T,
инициализирует ее нулевым значение типа T и возвращает ее адрес,
который представляет собой значение типа T.
```go
p := new(int)    // p, имеет тип *int, указывает на неименованную переменную типа int  
fmt.Println(*p)  // "0"
*p = 2           //  Устанавливает значение этой переменной равным 2
fmt.Println(*p)  // "2"
```