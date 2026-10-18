# 띵컷 이용 조건 · 오픈소스 고지

마지막으로 고친 날: 2026-10-18

## 이용 조건

1. **무료로 쓰세요.** 띵컷으로 만든 영상 · 자막 · 파일(결과물)의 권리는 모두 쓰는 분의 것이에요. 띵컷은 아무것도 요구하지 않아요. 로고나 사용 표시를 넣을 필요가 없어요.
2. **프로그램의 저작권은 만든 사람(띵지)에게 있어요.** 개인 · 업무 영상 편집에는 자유롭게 쓸 수 있어요. 다만 허락 없이 프로그램을 복사해 다시 올리거나, 팔거나, 고쳐서 나눠 주는 것은 안 돼요. 오픈소스 부분은 아래 각 라이선스를 따라요.
3. **있는 그대로 제공해요.** 잘 동작하도록 만들지만 모든 환경에서 오류가 없다고 약속하지는 못해요. 쓰다가 생긴 손해(파일 손상 · 시간 · 수익 등)는 법이 허락하는 범위에서 책임지지 않아요. 중요한 원본은 늘 백업해 주세요.
4. **자동 자막은 틀릴 수 있어요.** 올리기 전에 꼭 확인해 주세요.
5. 무료로 만드는 프로그램이라 기능을 바꾸거나 배포를 멈출 수 있어요.
6. 이 조건이 바뀌면 이 파일에 날짜와 함께 적어요. 궁금한 것은 [문의](https://github.com/myoungji-kim/ddingcut/issues/new)로 알려 주세요.

## 개인정보

- **영상 · 소리 · 자막은 이 컴퓨터 밖으로 나가지 않아요.** 가입도 없어요.
- 하루에 한 번 새 버전이 나왔는지 GitHub에 물어봐요. 이때 GitHub가 접속 주소(IP) 같은 기본 정보를 받아요. 영상 · 소리 · 자막은 보내지 않아요.
- 처음 켤 때 자막 도구와 모델을 내려받아요(GitHub · PyPI · Hugging Face에서 파일을 받는 요청이에요).
- 의견 · 문의 폼에 적은 내용(이메일은 선택)은 답을 드리는 데만 쓰고, 답을 드린 뒤 지워요.

## 오픈소스 고지

띵컷은 아래 오픈소스를 함께 쓰거나 내려받아 써요. 각 라이선스 전문은 설치 폴더의 해당 구성 요소 옆이나 링크에 있어요.

| 구성 요소 | 쓰는 곳 | 라이선스 |
| --- | --- | --- |
| [Electron](https://www.electronjs.org/) · Chromium | 프로그램 창 | MIT · BSD 등 (설치 폴더의 `LICENSE.electron.txt` · `LICENSES.chromium.html`) |
| [FFmpeg](https://ffmpeg.org/) | [영상으로 저장] | **GNU GPL v3**(x264 포함). 아래 *FFmpeg 소스 안내* |
| [uv](https://github.com/astral-sh/uv) | 자막 도구 설치 | MIT 또는 Apache-2.0 |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) · [CTranslate2](https://github.com/OpenNMT/CTranslate2) | 자막 만들기 | MIT |
| [PyAV](https://github.com/PyAV-Org/PyAV) | 소리 읽기 | BSD 3-Clause (LGPL의 FFmpeg 라이브러리 포함) |
| [Whisper large-v3-turbo](https://github.com/openai/whisper) | 말을 글로 | MIT |
| NVIDIA CUDA 런타임(cuBLAS · cuDNN · NVRTC) | 그래픽카드로 빠르게 | NVIDIA 라이선스. **쓰는 분의 컴퓨터에서 직접 내려받고, 띵컷이 다시 배포하지 않아요** |
| [Pretendard](https://github.com/orioncactus/pretendard) | 글꼴 | SIL OFL 1.1 (`fonts/OFL.txt`) |

### FFmpeg 소스 안내

설치 파일에 든 FFmpeg는 띵컷과 **별개의 프로그램**이고, 띵컷이 파일로 실행해서 써요. 띵컷 자체는 GPL이 아니에요.

- 소스: <https://github.com/FFmpeg/FFmpeg> (쓰는 정확한 판은 `ffmpeg -version`의 첫 줄에 적혀 있어요)
- 윈도 빌드를 만든 곳(스크립트 · 함께 든 라이브러리의 소스 안내): <https://github.com/BtbN/FFmpeg-Builds>
- 맥 빌드를 만든 곳: <https://ffmpeg.martin-riedl.de>
- 위에서 소스를 구할 수 없으면 [문의](https://github.com/myoungji-kim/ddingcut/issues/new)로 요청해 주세요. 이 판을 낸 날부터 3년 동안 보내 드려요.

## 상표

Premiere Pro와 Adobe는 Adobe의 상표예요. 띵컷은 Adobe와 관계없는 개인 프로젝트예요.
