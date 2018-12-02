# Compilador-Java
Analisador Léxico e Sintático com escopo reduzido da linguagem Java Para Cadeira de Compiladores na UEPB

Leitura para esse escopo:

    package Compiladores ;

    public class RodarPrograma {

        public static int a ;   

        public static int soma ( int a , int b ) {
            return ( a + b + c )  ;
        }


        public static void main ( String [ ]  args ) {

            int result = soma( 2 , 5 ) ;
            soma ( 2 , 5 ) ;

            if (result >  5) {

                if (result < 10) {
                    System.out.println("thiago");
                }
            } else {

                while (result < 5) {
                    result += 1 ;
                }
            }
        }
    }
