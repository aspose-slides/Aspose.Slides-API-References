---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Container of data point levels.
type: docs
url: /pt/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Contêiner de níveis de ponto de dados. Aplicado para séries Treeamp e Sunburst. A indexação dos níveis de ponto de dados começa em zero.

## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Retorna o objeto IChartDataPointLevel para o nível definido. |
| [getCount()](#getCount--) | Retorna a contagem de níveis de ponto de dados. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


Retorna o objeto IChartDataPointLevel para o nível definido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | int |  |

**Retorna:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Retorna a contagem de níveis de ponto de dados.

**Retorna:**
int