---
title: Contains()
second_title: Referência da API Aspose.Slides para C++
description: Determina se a coleção contém um valor específico.
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) método

Determina se a coleção contém um valor específico.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O objeto a ser localizado na coleção. |

### Valor de Retorno

true se *item* for encontrado na coleção; caso contrário, false.

## Observações

Exemplo: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)