---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa uma coleção de pontos para dividir ponto em um gráfico de barra-de-torta ou torta-de-torta com divisão personalizada.
type: docs
url: /pt/com.aspose.slides/piesplitcustompointcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Representa uma coleção de pontos para dividir ponto em um gráfico de barra-de-torta ou torta-de-torta com divisão personalizada.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o ponto de dados do gráfico para o índice especificado. |
| [add(int dataPointIndex)](#add-int-) | Adiciona ponto de dados pelo seu índice na coleção de pontos da série pai. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Adiciona ponto de dados à coleção. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Remove item da coleção. |
| [remove(int dataPointIndex)](#remove-int-) | Remove item da coleção pelo seu índice na coleção de pontos da série pai. |
| [clear()](#clear--) | Remove todos os itens do [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico. |
| [size()](#size--) | Retorna ou define a contagem de pontos de dados do gráfico. |
| [isReadOnly()](#isReadOnly--) | Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Retorna o ponto de dados do gráfico para o índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice. |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ponto de dados do gráfico.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Adiciona ponto de dados pelo seu índice na coleção de pontos da série pai.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPointIndex | int | Índice do ponto de dados na coleção de pontos da série pai. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Adiciona ponto de dados à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Ponto de dados a ser adicionado. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Remove item da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Ponto de dados a ser removido. |

**Retorna:**
boolean - verdadeiro se o item foi removido com sucesso; caso contrário, falso. Este método também retorna falso se o item não for encontrado em System.Collections.Generic.List{T}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Remove item da coleção pelo seu índice na coleção de pontos da série pai.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPointIndex | int | Índice do ponto de dados na coleção de pontos da série pai. |
### clear() {#clear--}
```
public final void clear()
```

Remove todos os itens do [IGenericCollection](../../com.aspose.slides/igenericcollection).
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | O objeto a ser localizado no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | O Array unidimensional que será o destino dos elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). O Array deve ter indexação baseada em zero. |
| arrayIndex | int | O índice baseado em zero no array onde a cópia começa. |
### size() {#size--}
```
public final int size()
```

Retorna ou define a contagem de pontos de dados do gráfico. int somente leitura.

**Retorna:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. boolean somente leitura.

**Retorna:**
boolean - verdadeiro se o [IGenericCollection](../../com.aspose.slides/igenericcollection) for somente leitura; caso contrário, falso.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). boolean somente leitura.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Object somente leitura.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Um java.util.Iterator para a coleção inteira.