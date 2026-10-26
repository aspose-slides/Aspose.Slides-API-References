---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Contêiner gerenciado dos valores dos níveis de categoria do gráfico.
type: docs
url: /pt/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Contêiner gerenciado dos valores dos níveis de categoria do gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataCell object for defined level. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Sets grouping item for defined level. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Delete grouping item for defined level. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Retorna o objeto IChartDataCell para o nível definido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | int |  |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Define o item de agrupamento para o nível definido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | int | Nível de categoria int |
| value | java.lang.Object | Objeto do item de agrupamento |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Exclui o item de agrupamento para o nível definido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | int | Nível de categoria int |