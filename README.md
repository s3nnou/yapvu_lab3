# yapvu_lab3
Вариант 3 
 
Написать Windows-приложение, работающее под управлением меню: 
Файл 
   Новый 
   Открыть 
   Сохранить 
   Выход 
Обработка матрицы 
    Сумма 
    Произведение… 
Уплотнить   
 Об авторе 
Для решения задачи создать класс «Матрица», в котором описать следующие элементы: закрытое поле – матрица целых чисел, индексатор для доступа к элементам поля-массива,  конструктор с параметрами, методы для поиска суммы элементов матрицы, перегруженные методы для вычисления произведения элементов, принадлежащих заданному интервалу (границы интервала передаются в метод в качестве параметров) и для вычисления произведения элементов, расположенных выше побочной диагонали (с проверкой, является ли матрица квадратной); уплотнить заданную матрицу, удаляя из нее строки и столбцы заполненные нулями. 
При выполнении команды Файл - Новый открывается таблица DataGridView для ввода матрицы, появляется кнопка Сохранить, кнопка Обработка и панель с переключателями для выбора вида вычислений в матрице. Пользователь получает возможность ввода матрицы. 
При выполнении команды Файл – Открыть открывается диалоговое окно открытия файла. После выбора файла открывается  таблица DataGridView с загруженной матрицей, появляется кнопка Обработка и панель с переключателями для выбора вида вычислений в матрице. 
При выполнении команды Файл – Сохранить открывается диалоговое окно сохранения файла. После ввода имени матрица сохраняется в соответствующем файле. То же самое происходит при нажатии кнопки Сохранить. 
	При 	выполнении 	команды 	Обработка 	матрицы 	–    
Произведение…  появляется окно с переключателями, определяющими, какой вид произведения нужно найти. 
При выполнении команды Обработка матрицы – Уплотнить – исходная матрица и уплотненная выводятся в новом окне в таблицах DataGridView. 
При выполнении команды Об авторе открывается окно с информацией о разработчике программы с фотографией. 

