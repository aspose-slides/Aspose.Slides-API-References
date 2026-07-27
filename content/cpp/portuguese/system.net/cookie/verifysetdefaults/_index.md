---
title: VerifySetDefaults()
second_title: Referência da API Aspose.Slides para C++
description: Verifica e define os valores padrão do atributo.
type: docs
weight: 482
url: /pt/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) método

Verifica e define os valores padrão do atributo.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | A especificação do cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A instância da classe Uri que é usada para inicializar os campos internos. |
| isLocalDomain | **bool** | Um valor que indica se o cookie é inserido no domínio local. |
| localDomain | [String](../../../system/string/) | Um nome de domínio local. |
| setDefault | **bool** | Um valor que indica se os atributos do cookie devem ser inicializados usando seus valores padrão. |
| shouldThrow | **bool** | Um valor que indica se uma exceção deve ser lançada quando os valores especificados são inválidos. |

### Valor de Retorno

True quando todos os valores são válidos, caso contrário false.

## Veja Também

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)