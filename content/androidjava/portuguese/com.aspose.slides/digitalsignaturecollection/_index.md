---
title: DigitalSignatureCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de assinaturas digitais anexadas a um documento.
type: docs
url: /pt/com.aspose.slides/digitalsignaturecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

Representa uma coleção de assinaturas digitais anexadas a um documento.
## Methods

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna a assinatura por índice. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | Adiciona a assinatura ao final da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove a assinatura no índice especificado. |
| [clear()](#clear--) | Remove todas as assinaturas da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [size()](#size--) | Retorna o número de elementos na coleção. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

Retorna a assinatura por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

Adiciona a assinatura ao final da coleção.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Assinatura a ser adicionada. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove a assinatura no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da assinatura que deve ser excluída. |
### clear() {#clear--}
```
public final void clear()
```

Remove todas as assinaturas da coleção.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Um java.util.Iterator para a coleção inteira.
### size() {#size--}
```
public final int size()
```

Retorna o número de elementos na coleção. int somente leitura.

**Retorno:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). boolean somente leitura.

**Retorno:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Object somente leitura.

**Retorno:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |