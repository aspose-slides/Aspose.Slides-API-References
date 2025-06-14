---  
title: SetColumnsAlignment
second_title: Aspose.Sildes for .NET API Reference  
description: Установить горизонтальное выравнивание заданных столбцов
type: docs
weight: 200  
url: /ru/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---  

## IMathMatrix.SetColumnsAlignment method  

Установить горизонтальное выравнивание заданных столбцов  

```csharp  
public void SetColumnsAlignment(int columnIndex, uint columnsCount, MathHorizontalAlignment val)  
```  

| Параметр | Тип | Описание |  
| --- | --- | --- |  
| columnIndex | Int32 | Индекс первого столбца для установки выравнивания, начиная с нуля |  
| columnsCount | UInt32 | Количество столбцов для задания выравнивания |  
| val | MathHorizontalAlignment | Новое значение горизонтального выравнивания указанного столбца |  

### Примеры  

Пример:  

```csharp  
[C#]  
IMathMatrix matrix = new MathMatrix(2, 3);  
matrix.SetColumnAlignment(0, 3, MathHorizontalAlignment.Left);  
```  

### См. также  

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)  
* interface [IMathMatrix](../../imathmatrix)  
* namespace [Aspose.Slides.MathText](../../imathmatrix)  
* assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  