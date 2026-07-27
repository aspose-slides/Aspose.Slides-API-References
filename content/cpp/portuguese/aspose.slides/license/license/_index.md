---
title: License()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância desta classe.
type: docs
weight: 1
url: /pt/aspose.slides/license/license/
---
## License::License() construtor

Inicializa uma nova instância desta classe.

```cpp
Aspose::Slides::License::License()
```

## Observações

Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém o assembly chamador, na pasta do assembly de entrada e então nos recursos incorporados do assembly chamador. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Ver Também

* Classe [License](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)