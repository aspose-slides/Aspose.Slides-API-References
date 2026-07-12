---
title: Tab
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma tabulação para um texto.
type: docs
url: /pt/com.aspose.slides/tab/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as interfaces implementadas:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Representa uma tabulação para um texto.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Cria uma nova Tab |
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Retorna ou define a posição de uma tabulação. |
| [setPosition(double value)](#setPosition-double-) | Retorna ou define a posição de uma tabulação. |
| [getAlignment()](#getAlignment--) | Retorna ou define o estilo de alinhamento de uma tabulação. |
| [setAlignment(int value)](#setAlignment-int-) | Retorna ou define o estilo de alinhamento de uma tabulação. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compara a instância atual com outro objeto do mesmo tipo. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Cria uma nova Tab

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | double | Posição da tabulação. |
| align | int | Alinhamento. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Retorna ou define a posição de uma tabulação. Atribuir esta propriedade pode mudar o índice da tabulação na coleção e invalidar o Enumerator. Leitura/gravação double.

**Retorna:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Retorna ou define a posição de uma tabulação. Atribuir esta propriedade pode mudar o índice da tabulação na coleção e invalidar o Enumerator. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Retorna ou define o estilo de alinhamento de uma tabulação. Leitura/gravação [TabAlignment](../../com.aspose.slides/tabalignment).

**Retorna:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Retorna ou define o estilo de alinhamento de uma tabulação. Leitura/gravação [TabAlignment](../../com.aspose.slides/tabalignment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Compara a instância atual com outro objeto do mesmo tipo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | Um objeto para comparar com esta instância. |

**Retorna:**
int - Um inteiro de 32 bits que indica a ordem relativa dos comparandos. O valor de retorno tem os seguintes significados:

 * < 0 - Esta instância é menor que obj.
 * = 0 - Esta instância é igual a obj.
 * > 0 - Esta instância é maior que obj.