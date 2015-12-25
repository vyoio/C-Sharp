          // Relational Operators : > < >= <= == !=
          // Logical Operators : && || ^ !

// If Statement
            int age = 48;
            if ((age >= 11) && (age <= 20))
            {
                Console.WriteLine("Gen Z");
            }
            else if ((age > 21) && (age < 33))
            {
                Console.WriteLine("Gen Y");
            }
            else {
                Console.WriteLine("Gen X");
            }
            if ((age < 14) || (age > 50))
            {
                Console.WriteLine("Baby Boomer?");
            }
            Console.WriteLine("! true = " + (!true));
            Console.ReadKey();
