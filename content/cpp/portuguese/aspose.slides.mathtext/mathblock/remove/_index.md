---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove a primeira ocorrência de um objeto específico da coleção.
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) método


Remove a primeira ocorrência de um objeto específico da coleção.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O objeto a ser removido da coleção. |

### Valor de Retorno

true se *item* for removido com sucesso da coleção; caso contrário, false. Este método também retorna false se *item* não for encontrado na coleção original.
## Observações



Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)