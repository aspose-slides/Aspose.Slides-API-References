---  
title: IPoint
second_title: Aspose.Slides para .NET API Reference  
description: Representar punto de animación.
type: docs  
weight: 460  
url: /es/aspose.slides.animation/ipoint/
---  

## Interfaz IPoint  

Representar punto de animación.  

```csharp  
public interface IPoint  
```  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| [Formula](../../aspose.slides.animation/ipoint/formula) { get; set; } | Las fórmulas dentro de los valores, atributos from, to, by pueden estar compuestas por estos: Operadores aritméticos estándar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod) Constantes: ‘pi’ ‘e’ Operadores condicionales: ‘abs’, ‘min’, ‘max’, ‘?’ (if) Operadores de comparación: '==', '&gt;=', '', '!=', '!' Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’ Logaritmo natural ‘ln()’ Referencias a propiedades (propiedades soportadas por el anfitrión) por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Leer/escribir Cadena. |  
| [Time](../../aspose.slides.animation/ipoint/time) { get; set; } | Representa valor de tiempo. Leer/escribir Simple. |  
| [Value](../../aspose.slides.animation/ipoint/value) { get; set; } | Representa valor del punto. Solo: bool, ColorFormat, float, int, string. Leer/escribir Objeto. |  

### Véase También  

* espacio de nombres [Aspose.Slides.Animation](../../aspose.slides.animation)  
* ensamblado [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  