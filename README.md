# Make-a-Word
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _9.Make_a_Word
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());
            string word = string.Empty;


            for (int i = 0; i < n; i++)
            {
                char simbol = char.Parse(Console.ReadLine());                
                word += simbol;
            }
            Console.WriteLine($"The word is: {word}");
        }
    }
}
