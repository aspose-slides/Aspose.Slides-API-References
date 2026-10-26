---
title: SecurityPermissionFlag
second_title: Aspose.Slides para C++ Referência da API
description: Bandeiras da permissão de segurança.
type: docs
weight: 27
url: /pt/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Bandeiras da permissão de segurança.

```cpp
enum class SecurityPermissionFlag
```

### Values

| Nome | Valor | Descrição |
| --- | --- | --- |
| NoFlags | 0 | Sem acesso. |
| Assertion | 1 | Afirmar que a permissão foi concedida. |
| UnmanagedCode | 2 | Chamar código não gerenciado. |
| SkipVerification | 4 | Ignorar verificação de código. |
| Execution | 8 | Executar código. |
| ControlThread | 16 | Realizar operações em threads. |
| ControlEvidence | 32 | Controlar ou alterar evidências do CLR. |
| ControlPolicy | 64 | Visualizar e alterar a política. |
| SerializationFormatter | 128 | Serializar. |
| ControlDomainPolicy | 256 | Definir política de domínio. |
| ControlPrincipal | 512 | Controlar objeto principal. |
| ControlAppDomain | 1024 | Controlar domínio de aplicação. |
| RemotingConfiguration | 2048 | Configurar remoting. |
| Infrastructure | 4096 | Integrar-se à infraestrutura do CLR. |
| BindingRedirects | 8192 | Realizar redirecionamento explícito de binding. |
| AllFlags | 16383 | Irrestrito. |

## Veja também

* Namespace [System::Security::Permissions](../)
* Biblioteca [Aspose.Slides](../../)