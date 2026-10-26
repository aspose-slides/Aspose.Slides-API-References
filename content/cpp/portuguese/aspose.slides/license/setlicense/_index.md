---
title: SetLicense()
second_title: Referência da API Aspose.Slides para C++
description: Licencia o componente.
type: docs
weight: 14
url: /pt/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) método


Licencia o componente.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Pode ser um nome de arquivo completo ou abreviado ou o nome de um recurso incorporado. Use uma cadeia vazia para mudar para o modo de avaliação. |
## Observações



Tenta encontrar a licença nos seguintes locais:

1. Caminho explícito.

2. A pasta da assembly do componente.

3. A pasta da assembly chamadora do cliente.

4. A pasta da assembly de entrada.

5. Um recurso incorporado na assembly chamadora do cliente.

**Nota:**No .NET Compact Framework, tenta encontrar a licença apenas nesses locais:

1. Caminho explícito.

2. Um recurso incorporado na assembly chamadora do cliente.

Neste exemplo, será feita uma tentativa de encontrar um arquivo de licença chamado MyLicense.lic na pasta que contém o componente, na pasta que contém a assembly chamadora, na pasta da assembly de entrada e, por fim, nos recursos incorporados da assembly chamadora. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) método


Licencia o componente.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo que contém a licença. |
## Observações



Use este método para carregar uma licença a partir de um fluxo.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [License](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)