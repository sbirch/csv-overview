csv-overview
============

Get the vital statistics of a CSV file.

For example (from the NYPL menu's database):

	Dish.csv
	351769 entries
		(0) id: 351769 unique (100.00%)
			0 empty (0.00%),
			351769 numeric (100.00%)
			e.g. ['254113', '349976', '228305', '315656', '248210']
		(1) name: 351734 unique (99.99%)
			0 empty (0.00%),
			59 numeric (0.02%)
			e.g. ['Pineapple Wheel', 'Kase, Fruchte, Kaffee', 'Cocoanut Pie per cut', 'Pernod for Absinthe', 'Hot Chicken Sandwich']
		(2) description: 1 unique (0.00%)
			351769 empty (100.00%),
			0 numeric (0.00%)
			e.g. ['', '', '', '', '']
		(3) menus_appeared: 481 unique (0.14%)
			0 empty (0.00%),
			351769 numeric (100.00%)
			e.g. ['357', '395', '328', '283', '195']
		(4) times_appeared: 505 unique (0.14%)
			0 empty (0.00%),
			351769 numeric (100.00%)
			e.g. ['1360', '516', '155', '434', '85']
		(5) first_appeared: 140 unique (0.04%)
			0 empty (0.00%),
			351769 numeric (100.00%)
			e.g. ['1913', '1943', '1982', '1908', '1865']
		(6) last_appeared: 140 unique (0.04%)
			0 empty (0.00%),
			351769 numeric (100.00%)
			e.g. ['2004', '1920', '1981', '1904', '1998']
		(7) lowest_price: 633 unique (0.18%)
			6211 empty (1.77%),
			345558 numeric (98.23%)
			e.g. ['19.25', '135.0', '2.19', '4.51', '12.95']
		(8) highest_price: 685 unique (0.19%)
			6211 empty (1.77%),
			345558 numeric (98.23%)
			e.g. ['2.3', '850.0', '6.99', '4.0', '1100.0']
	Numerics:
		id: 1.000000 - 410825.000000 (avg: 209010.0423857702, non-0 avg: 209010.0423857702, median: 209171.000000, mode: '287144')
		menus_appeared: 0.000000 - 7195.000000 (avg: 2.9667025803865603, non-0 avg: 2.9704264960378906, median: 1.000000, mode: '1')
		times_appeared: -1.000000 - 7901.000000 (avg: 3.0338801884191047, non-0 avg: 3.0363488419070053, median: 1.000000, mode: '1')
		first_appeared: 0.000000 - 2012.000000 (avg: 1744.2648584724634, non-0 avg: 1930.0559754896872, median: 1900.000000, mode: '1900')
		last_appeared: 0.000000 - 2012.000000 (avg: 1747.0906845117108, non-0 avg: 1933.1827955974545, median: 1900.000000, mode: '1900')
		lowest_price: 0.000000 - 9500.000000 (avg: 0.9507477181834131, non-0 avg: 2.526713734176425, median: 0.000000, mode: '0.0')
		highest_price: 0.000000 - 9500.000000 (avg: 1.517539747307291, non-0 avg: 3.915697196875889, median: 0.000000, mode: '0.0')
