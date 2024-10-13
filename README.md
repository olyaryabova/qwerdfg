////задание 1
//class Program
//{

//    static void Main()
//    {
//        Console.WriteLine("Введите первое число: ");
//        int num1 = Convert.ToInt32(Console.ReadLine());

//        Console.WriteLine("Введите второе число: ");
//        int num2 = Convert.ToInt32(Console.ReadLine());

//        double sum = SumNumbers(num1, num2);
//        Console.WriteLine("Сумма чисел: " + sum);
//    }

//    static double SumNumbers(double num1, double num2)
//    {
//        return num1 + num2;
//    }
//}

////задание 2

//class CheckEvenNumber
//{
//    static void Main(string[] args)
//    {
//        Console.WriteLine("Введите число: ");
//        int number = Convert.ToInt32(Console.ReadLine());

//        if (Form(number))
//        {
//            Console.WriteLine("Число четное");
//        }
//        else
//        {
//            Console.WriteLine("Число нечетное");
//        }
//    }

//    static bool Form(int number)
//    {
//        return number % 2 == 0;
//    }
//}


////задание 3

//class Programm
//{
//    static void Main()
//    {
//        Console.WriteLine("Введите число:");
//        int number = Convert.ToInt32(Console.ReadLine());
//        long factorial = Fact(number);

//        Console.WriteLine($"Факториал числа {number} = {factorial}");
//    }

//    static int Fact(int n)
//    {
//        if (n == 0)
//            return 1;
//        else
//            return n * Fact(n - 1);
//    }
//}


////задание 4
//class Prog
//{
//    static void Main()
//    {
//        Console.WriteLine("Введите строку:");
//        string str = Console.ReadLine();
//        string reversstr = Reversestr(str);

//        Console.WriteLine("Перевернутая строка: " + reversstr);
//    }

//    static string Reversestr(string str)
//    {
//        char[] charArray = str.ToCharArray();
//        Array.Reverse(charArray);
//        return new string(charArray);
//    }
//}

////задание 6

//static void Massive()
//{
//    Console.WriteLine("Введите массив: ");

//    int num = int.Parse(Console.ReadLine());
//    double[] array = new double[num];

//    for (int i = 0; i < array.Length; i++)
//    {

//        array[i] = double.Parse(Console.ReadLine());
//    }
//    Console.WriteLine("Среднее число {0}", (array.Sum() / array.Length));
//}
