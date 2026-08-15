---
title: SecurityPermissionFlag
second_title: Aspose.Slides for C++ API 參考文件
description: 安全權限的旗標。
type: docs
weight: 27
url: /zh-hant/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag 列舉

安全權限的旗標。

```cpp
enum class SecurityPermissionFlag
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| NoFlags | 0 | 無存取。 |
| Assertion | 1 | 斷言已授予權限。 |
| UnmanagedCode | 2 | 呼叫非受管理程式碼。 |
| SkipVerification | 4 | 跳過程式碼驗證。 |
| Execution | 8 | 執行程式碼。 |
| ControlThread | 16 | 對執行緒執行操作。 |
| ControlEvidence | 32 | 控制或更改 CLR 證據。 |
| ControlPolicy | 64 | 檢視與變更政策。 |
| SerializationFormatter | 128 | 序列化。 |
| ControlDomainPolicy | 256 | 設定網域政策。 |
| ControlPrincipal | 512 | 控制主體物件。 |
| ControlAppDomain | 1024 | 控制應用程式網域。 |
| RemotingConfiguration | 2048 | 設定遠端。 |
| Infrastructure | 4096 | 接入 CLR 基礎結構。 |
| BindingRedirects | 8192 | 執行明確的繫結重新導向。 |
| AllFlags | 16383 | 未受限制。 |

## 另請參閱

* 命名空間 [System::Security::Permissions](../)
* 函式庫 [Aspose.Slides](../../)