# Tarea_colaborativa_mariscal_antonio-
un algoritmo con un error común que suele pasar a cualquier pricipiante

Algoritmo ejercicio_20
	
		Escribir "Introduce el nombre del alumno"
		Leer alumno
		
		Mientras alumno<>"" Hacer
			
			Escribir "Introduce la nota practica"
			leer nota_practica
			
			Escribir "Introduce la nota de problemas"
			leer nota_problemas		
			Escribir "Introduce la nota de teoria"
			Leer nota_teoria
			
			si (nota_practica<=10 y nota_practica>=0) y (nota_problemas<=10 y nota_problemas>=0) y (nota_teoria<=10 y nota_teoria>=0) Entonces
				Escribir "El alumno " alumno
				Escribir "La nota practica es " nota_practica
				Escribir "La nota de problemas es " nota_problemas
				Escribir "La nota de teoria es " nota_teoria
				nota_practica<-nota_practica*0.1
				nota_problemas<-nota_problemas*0.5
				nota_teoria<-nota_teoria*0.4
				nota_problemas<-nota_practica+nota_problemas+nota_teoria/3
				Escribir "La nota final es " nota_problemas
			Sino
				Escribir "Has escrito una nota incorrecta, vuelve a intentarlo"

			FinSi
			Escribir "Introduce el nombre de otro alumno"
			Leer alumno
		FinMientras
FinAlgoritmo

