---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Contenedor administrado de los valores de los niveles de categoría del gráfico.
type: docs
url: /es/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Contenedor administrado de los valores de los niveles de categoría del gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Devuelve el objeto IChartDataCell para el nivel definido. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Establece el elemento de agrupación para el nivel definido. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Elimina el elemento de agrupación para el nivel definido. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Devuelve el objeto IChartDataCell para el nivel definido.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| level | int |  |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Establece el elemento de agrupación para el nivel definido.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| level | int | Nivel de categoría int |
| value | java.lang.Object | Objeto de elemento de agrupación |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Elimina el elemento de agrupación para el nivel definido.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| level | int | Nivel de categoría int |