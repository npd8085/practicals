# practicals
LT practical- MAking own langauge compiler using flex and yacc tools 
have separate files for input to flex and yacc , named as calc.lex and calc.y respectively.
steps to be applied are- 
1) yacc -d calc.yacc 
2) flex calc.lex 
3) gcc y.tab.c lex.yy.c  -o mycompiler
4) ./mycompiler 
