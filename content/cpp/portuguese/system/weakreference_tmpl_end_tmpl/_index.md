---
title: WeakReference<>
second_title: Referência da API Aspose.Slides para C++
description: Representa uma referência fraca, que referencia um objeto enquanto ainda permite que esse objeto seja excluído.
type: docs
weight: 1522
url: /pt/system/weakreference_tmpl_end_tmpl/
---
## classe WeakReference<>

Representa uma referência fraca, que referencia um objeto enquanto ainda permite que esse objeto seja excluído.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Obtém uma indicação se o objeto referenciado pelo objeto WeakReference atual foi excluído. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Obtém o objeto (o alvo) referenciado pelo objeto WeakReference atual. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Define o objeto (o alvo) referenciado pelo objeto WeakReference atual. |
|  [WeakReference](./weakreference/)() | Construtor padrão. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Construtor a partir de nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Inicializa uma nova instância da classe WeakReference, referenciando o objeto especificado. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Inicializa uma nova instância da classe WeakReference, referenciando o objeto especificado. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)