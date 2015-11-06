/---------------------------------------Group Information----------------------------------------/

Group name:	SDE(Stevens Dota Elites/Software Development Engineers)

Members:	Gong Cheng 	10390440
		Lingzhi Yuan	10391683
		Yanjun Wu	10392467
		Zhe Xu		10393213

/--------------------------------------Submission contents---------------------------------------/

engine.cpp:				-The Query Processing Engine source code for our project.
Queries.txt:				-6 sample queries(including Question description, EMF, input
					 format, and Standard SQL) for our project.
EMFquery.txt:				-Input file for our project.
Sample.pgc:				-The program used as the sample output of our engine.
CS562B-SDE final presentation.pptx:	-Our final presentation for the project.
Outputs folder:				-Output files for our sample queries.
Demos folder:				-Demos files used for demonstrating our project

/------------------------------Application development environment-------------------------------/

Programming language:		-C++ for the engine, and C for the generated program
Compiler:			-g++/gcc (Ubuntu 4.8.2-19ubuntu1) 4.8.2
Database:			-psql (PostgreSQL) 9.3.6
Preprocessor for embedded SQL:	-ecpg (PostgreSQL 9.2.4) 4.8.0
Libraries:			-All standard libraries
Operating System:		-Linux(preferred Ubuntu)

/------------------------------------------Instructions------------------------------------------/

Input format: 			-Operands must be in the order of S, V, n, F, o, G, W, T.
(There are 6 examples in	--S is list of projected attributes for the query output.
Queries.txt for reference)	--V is list of grouping attributes				
				--n is Number of grouping variables
 				--F is list of aggregate functions
				--o is list(s) of predicates to define the ranges for the 
				  grouping variables
				--G is predicate for the having clause
				--W is conditions in where clause
				--T is table name
				------------------------------------------------------------------
				-The symbol of operand occupies a whole line, the actual operands
				 should be in the line right after their symbols.
				-All aggregate functions are in the following format: a_b_c, which
				 a is the aggregate function, b is the number indicates the grouping
				 variable, c is the column name.
				-All white spaces are not allowed unless specified below.
				-In S, V and F, one comma following by a single space between two
				 adjacent elements.
				-For o, line should begin with number indicates the grouping vari-
				 able. Numbers for these lines should be sequential and start at 1.
				 (0 is reseverd for grouping attributes.) One single space between 
				 two adjacent elements. Variable prefixes are all left out.
				-For G and W, a single space between two adjacent elements.
				-For T, only one table name is allowed.
				-All letters are lower case letters.
				-There are 6 sample queries and inputs in the Queries.txt file.
				-"month","day","year" should be "mm", "dd", "yy".
				-All strings should be surrounded by a pair of single quotes.
				-All "not equal" should be represented in "<>" rather than "!=".
				-Single element should contain no white space.
				  
				
