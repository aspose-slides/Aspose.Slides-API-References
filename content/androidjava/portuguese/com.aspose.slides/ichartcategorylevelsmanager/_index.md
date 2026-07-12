---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Container gerenciado dos valores dos níveis de categoria do gráfico.
type: docs
url: /pt/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Container gerenciado dos valores dos níveis de categoria do gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Retorna objeto IChartDataCell para o nível definido. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Define item de agrupamento para o nível definido. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Exclui item de agrupamento para o nível definido. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Retorna objeto IChartDataCell para o nível definido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | int |  |

**Retorno:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Define item de agrupamento para o nível definido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | int | Nível de categoria int |
| value | java.lang.Object | Objeto de item de agrupamento |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Exclui item de agrupamento para o nível definido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | int | Nível de categoria int |