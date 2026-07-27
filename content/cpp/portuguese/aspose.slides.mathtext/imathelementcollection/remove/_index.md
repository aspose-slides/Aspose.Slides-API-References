---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove a primeira ocorrência de um objeto específico da coleção.
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) method


Remove a primeira ocorrência de um objeto específico da coleção.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O objeto a ser removido da coleção. |

### Valor de Retorno

true se *item* foi removido com sucesso da coleção; caso contrário, false. Este método também retorna false se *item* não for encontrado na coleção original.
## Observações



Exemplo: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)