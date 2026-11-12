# Whisper (CTranslate2) mirror

Mirror of the [faster-whisper](https://github.com/SYSTRAN/faster-whisper) CTranslate2 conversions of
OpenAI Whisper models, packaged as zip files in the Releases of this repository.

| Asset | Source | Size |
|---|---|---|
| `whisper-base.zip` | [Systran/faster-whisper-base](https://huggingface.co/Systran/faster-whisper-base) | ~148 MB |
| `whisper-small.zip` | [Systran/faster-whisper-small](https://huggingface.co/Systran/faster-whisper-small) | ~486 MB |

Usage:
```python
from faster_whisper import WhisperModel
model = WhisperModel("whisper-base", device="cpu", compute_type="int8")  # extracted folder
```

## License
The Whisper model weights are released by OpenAI under the MIT License; the CTranslate2
conversions are by SYSTRAN (MIT). See `LICENSE`. Files are unmodified.
