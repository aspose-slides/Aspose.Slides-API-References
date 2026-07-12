---
title: ITabEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que contém as propriedades de parada de tabulação dos textos efetivos.
type: docs
url: /pt/com.aspose.slides/itabeffectivedata/
---
**Todas as Interfaces Implementadas:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Objeto imutável que contém as propriedades de parada de tabulação do texto efetivo.

--------------------

Esta interface é usada como parte de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getPosition()](#getPosition--) | Retorna a posição de uma tabulação. |
| [getAlignment()](#getAlignment--) | Retorna o estilo de alinhamento de uma tabulação. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Retorna a posição de uma tabulação. Atribuir esta propriedade pode mudar o índice da tabulação na coleção e invalidar o Enumerator. Somente leitura double.

**Retorna:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Retorna o estilo de alinhamento de uma tabulação. Somente leitura [TabAlignment](../../com.aspose.slides/tabalignment).

**Retorna:**
int