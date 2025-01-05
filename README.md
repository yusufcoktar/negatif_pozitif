# negatif_pozitif
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp11
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("hadi bakalım sayıların pozitif negatifliklerine göre inceleyelim");
            Console.WriteLine("bir sayı gir");
            int name = Convert.ToInt32(Console.ReadLine());
            if (name == 0)
            {
                Console.WriteLine("sıfır");
            }
            if (name > 0)
            {
                Console.WriteLine("pozitif");
               
            }
            if (name < 0)
            {
                 Console.WriteLine("negatif");
            }
                Console.ReadKey();
           

        }
    }
}
