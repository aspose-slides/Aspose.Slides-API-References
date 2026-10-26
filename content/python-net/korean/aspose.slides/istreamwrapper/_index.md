---
title: IStreamWrapper class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/istreamwrapper/
---
## IStreamWrapper 클래스

Aspose.IO.Stream 래퍼 for COM 인터페이스.

IStreamWrapper 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`stream`](/slides/python-net/ko/aspose.slides/istreamwrapper/stream/) | 스트림을 가져옵니다.<br/> 읽기 전용 **io.RawIOBase**. |
| [`can_read`](/slides/python-net/ko/aspose.slides/istreamwrapper/can_read/) | 현재 스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다.<br/> 읽기 전용 **bool**. |
| [`can_seek`](/slides/python-net/ko/aspose.slides/istreamwrapper/can_seek/) | 현재 스트림이 탐색을 지원하는지 여부를 나타내는 값을 가져옵니다.<br/> 읽기 전용 **bool**. |
| [`can_write`](/slides/python-net/ko/aspose.slides/istreamwrapper/can_write/) | 현재 스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다.<br/> 읽기 전용 **bool**. |
| [`length`](/slides/python-net/ko/aspose.slides/istreamwrapper/length/) | 스트림의 바이트 길이를 가져옵니다.<br/> 읽기 전용 **int**. |
| [`position`](/slides/python-net/ko/aspose.slides/istreamwrapper/position/) | 현재 스트림 내 위치를 가져옵니다.<br/> 읽기 전용 **int**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`close(self)`](/slides/python-net/ko/aspose.slides/istreamwrapper/close/#) | 현재 스트림을 닫고 모든 리소스를 해제합니다. |
| [`flush(self)`](/slides/python-net/ko/aspose.slides/istreamwrapper/flush/#) | 이 스트림에 대한 모든 버퍼를 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 합니다. |
| [`read(self, buffer, offset, count)`](/slides/python-net/ko/aspose.slides/istreamwrapper/read/#bytes-int-int) | 현재 스트림에서 바이트 시퀀스를 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동합니다. |
| [`read_byte(self)`](/slides/python-net/ko/aspose.slides/istreamwrapper/read_byte/#) | 스트림에서 바이트를 읽고 스트림 내 위치를 1바이트 이동합니다. 스트림 끝에 도달하면 -1을 반환합니다. |
| [`seek(self, offset, origin)`](/slides/python-net/ko/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | 현재 스트림 내 위치를 설정합니다. |
| [`write(self, buffer, offset, count)`](/slides/python-net/ko/aspose.slides/istreamwrapper/write/#bytes-int-int) | 현재 스트림에 바이트 시퀀스를 기록하고, 기록된 바이트 수만큼 스트림 내 현재 위치를 이동합니다. |
| [`write_byte(self, value)`](/slides/python-net/ko/aspose.slides/istreamwrapper/write_byte/#int) | 스트림의 현재 위치에 바이트를 기록하고, 스트림 내 위치를 1바이트 이동합니다. |


### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)