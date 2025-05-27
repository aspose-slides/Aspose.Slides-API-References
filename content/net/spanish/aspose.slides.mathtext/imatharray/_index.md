---
title: IMathArray
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica un arreglo vertical de ecuaciones o cualquier objeto matemático
type: docs
weight: 7850
url: /es/aspose.slides.mathtext/imatharray/
---

## Interfaz IMathArray

Especifica un arreglo vertical de ecuaciones o cualquier objeto matemático

```csharp
public interface IMathArray : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/imatharray/arguments) { get; } | El conjunto de elementos del arreglo |
| [AsIMathElement](../../aspose.slides.mathtext/imatharray/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imatharray/basejustification) { get; set; } | Especifica la alineación del arreglo en relación con el texto circundante El texto fuera del arreglo puede estar alineado con la parte inferior, superior o el centro de un objeto de arreglo. Valor predeterminado: Centro |
| [MaximumDistribution](../../aspose.slides.mathtext/imatharray/maximumdistribution) { get; set; } | Distribución Máxima Cuando es verdadero, el arreglo se espacia a la máxima anchura del elemento contenedor(página, columna, celda, etc.). |
| [ObjectDistribution](../../aspose.slides.mathtext/imatharray/objectdistribution) { get; set; } | Distribución del Objeto Cuando es verdadero, el contenido del arreglo se espacia a la máxima anchura del objeto de arreglo. |
| [RowSpacing](../../aspose.slides.mathtext/imatharray/rowspacing) { get; set; } | Espaciado entre filas de un arreglo Se utiliza solo cuando RowSpacingRule se establece en 3 Exactamente en cuyo caso la unidad de medida son puntos o Múltiples en cuyo caso la unidad de medida son medios líneas. Predeterminado: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/imatharray/rowspacingrule) { get; set; } | El tipo de espaciado vertical entre elementos del arreglo |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### Véase también

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->