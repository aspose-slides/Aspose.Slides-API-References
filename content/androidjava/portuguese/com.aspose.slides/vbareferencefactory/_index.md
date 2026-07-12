---
title: VbaReferenceFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar referências de projetos VBA via interface COM
type: docs
url: /pt/com.aspose.slides/vbareferencefactory/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Permite criar referências de projetos VBA via interface COM
## Construtores

| Construtor | Descrição |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getInstance()](#getInstance--) | Instância estática da fábrica de referências de projetos VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Cria nova referência de biblioteca de tipos OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```

### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

Instância estática da fábrica de referências de projetos VBA. Somente leitura [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Retorna:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Cria nova referência de biblioteca de tipos OLE Automation.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Retorna:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nova referência de biblioteca de tipos OLE Automation