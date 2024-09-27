1-
public static void main(String[] Args) {
	Scanner sc = new Scanner(System.in);
	System.out.println("Insira um número");
	int num = sc.nextInt();
	if(num >= 0) {
	System.out.println(num + " não é negativo");
	} else {
	System.out.println(num + " é Negativo");
	}   
	}
 
-------------------------------------------------------------------------------------------
2-
	public static void main(String[] Args) {
		Scanner sc = new Scanner(System.in);  
	    System.out.println("Insira um número");
	    int num = sc.nextInt(); 
	    if(num%2 == 0) {
	    	System.out.println(num + " é par");
	    } else {
	    	System.out.println(num + " é ímpar");
	    } 
	}
-----------------------------------------------------------------------------------------------
3-    
	public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Digite o primeiro valor (A): ");
        int A = scanner.nextInt();
        System.out.print("Digite o segundo valor (B): ");
        int B = scanner.nextInt();
        if (A % B == 0 || B % A == 0) {
            System.out.println("Sao Multiplos");
        } else {
            System.out.println("Nao sao Multiplos");
        }
        scanner.close();
    }
-------------------------------------------------------------------------------------------------
4-
public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Digite a hora inicial do jogo: ");
        int horaInicial = scanner.nextInt();
        System.out.print("Digite a hora final do jogo: ");
        int horaFinal = scanner.nextInt();
        int duracao;
        if (horaInicial < horaFinal) {
            duracao = horaFinal - horaInicial;
        } 
        else {
            duracao = (24 - horaInicial) + horaFinal;
        }
        if (duracao == 0) {
            duracao = 24;
        }
        System.out.println("O jogo durou " + duracao + " hora(s).");
        scanner.close();
    }
--------------------------------------------------------------------------------------------------
5-
        public static void main(String[] args) {
	Scanner scanner = new Scanner(System.in);
        System.out.print("Digite um número inteiro: ");
        int n = scanner.nextInt();
        if(n >= 0 && n <= 25) {
        	System.out.println("Dentro do Intervalo [0,25]");
        } else if(n >= 25 && n <= 50) {
        	System.out.println("Dentro do Intervalo [25,50]");
        } else if(n >= 50 && n <= 75) {
        	System.out.println("Dentro do Intervalo [50,75]");
        } else if(n >= 75 && n <= 100) {
        	System.out.println("Dentro do Intervalo [75,100]");
        } else {
            System.out.println("Fora de intervalo");
        }
        scanner.close();
    }
--------------------------------------------------------------------------------------------------
