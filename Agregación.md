using System;

public class Departamento 
{
    public string Nombre{get; set;}
    public void MostrarProfesor(Profesor p) 
    {
        Console.WriteLine("Profesor: " + p.Nombre);
        Console.WriteLine("Departamento: " + Nombre);
    }
}
public class Profesor
{
    public string Nombre{get; set;}
}
class Program 
{
    static void Main()
    {
        Profesor profa =new Profesor(); 
        profa.Nombre="Melissa";
        Departamento Liderazgo =new Departamento();
        Liderazgo.Nombre="Liderazgo";
       
        Liderazgo.MostrarProfesor(profa);
        
    }
}# Agregaci-n-UML-Melissa
