---
title: Igual
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina si las dos instancias de IBaseSlide son iguales. El valor de retorno se calcula en función de la estructura de las diapositivas y el contenido estático. Dos diapositivas son iguales si todos los estilos, textos, animaciones y otras configuraciones son iguales, etc. La comparación no toma en cuenta los valores de identificador únicos, p. ej. SlideId y contenido dinámico, p. ej. el valor de la fecha actual en Date Placeholder.
type: docs
weight: 130
url: /es/aspose.slides/baseslide/equals/
---

## Método BaseSlide.Equals

Determina si las dos instancias de IBaseSlide son iguales. El valor de retorno se calcula en función de la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todos los estilos, textos, animaciones y otras configuraciones son iguales, etc. La comparación no toma en cuenta los valores de identificador únicos, p. ej. SlideId y contenido dinámico, p. ej. el valor de la fecha actual en Date Placeholder.

```csharp
public bool Equals(IBaseSlide slide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | IBaseSlide | El IBaseSlide a comparar con el IBaseSlide actual. |

### Valor de Retorno

**true** si el IBaseSlide especificado es igual al IBaseSlide actual; de lo contrario, **false**.

### Ejemplos

El siguiente ejemplo muestra cómo comparar dos diapositivas.

```csharp
[C#]
using (Presentation presentation1 = new Presentation("AccessSlides.pptx"))
{
	using (Presentation presentation2 = new Presentation("HelloWorld.pptx"))
	{
		for (int i = 0; i < presentation1.Masters.Count; i++)
		{
			for (int j = 0; j < presentation2.Masters.Count; j++)
			{
				if (presentation1.Masters[i].Equals(presentation2.Masters[j]))
					Console.WriteLine(string.Format("SomePresentation1 MasterSlide#{0} es igual a SomePresentation2 MasterSlide#{1}", i, j));
			}
		}
	}
}
```

### Véase También

* interfaz [IBaseSlide](../../ibaseslide)
* clase [BaseSlide](../../baseslide)
* namespace [Aspose.Slides](../../baseslide)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->