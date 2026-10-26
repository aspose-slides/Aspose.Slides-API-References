---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API hivatkozás
description: Megadja a hibasáv értékeket.
type: docs
url: /hu/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Megadja a hibasáv értékeket. Csak akkor kell használni, ha a hibasáv érték típusa Custom.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getXMinus()](#getXMinus--) | Megadja a hibasáv értékét a negatív irányban. |
| [getYMinus()](#getYMinus--) | Megadja a hibasáv értékét a negatív irányban. |
| [getXPlus()](#getXPlus--) | Megadja a hibasáv értékét a pozitív irányban. |
| [getYPlus()](#getYPlus--) | Megadja a hibasáv értékét a pozitív irányban. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```


Megadja a hibasáv értékét a negatív irányban. Elérhető, ha a hibasáv érték típusa Custom és az ErrorBarsXFormat engedélyezett. Bármely más esetben ez a tulajdonság null értéket ad vissza. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```


Megadja a hibasáv értékét a negatív irányban. Elérhető, ha a hibasáv érték típusa Custom és az ErrorBarsYFormat engedélyezett. Bármely más esetben ez a tulajdonság null értéket ad vissza. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```


Megadja a hibasáv értékét a pozitív irányban. Elérhető, ha a hibasáv érték típusa Custom és az ErrorBarsXFormat engedélyezett. Bármely más esetben ez a tulajdonság null értéket ad vissza. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```


Megadja a hibasáv értékét a pozitív irányban. Elérhető, ha a hibasáv érték típusa Custom és az ErrorBarsYFormat engedélyezett. Bármely más esetben ez a tulajdonság null értéket ad vissza. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)