# VCTK RECIPE

This is the recipe of the English multi-speaker TTS model with [VCTK](http://www.udialogue.org/download/cstr-vctk-corpus.html) corpus.

See the following pages for the usage:
- [How to run the recipe](../../TEMPLATE/tts1/README.md#how-to-run)
- [How to train FastSpeech](../../TEMPLATE/tts1/README.md#fastspeech-training)
- [How to train FastSpeech2](../../TEMPLATE/tts1/README.md#fastspeech2-training)

See the following pages before asking the question:
- [ESPnet2 Tutorial](https://espnet.github.io/espnet/espnet2_tutorial.html)
- [ESPnet2 TTS FAQ](../../TEMPLATE/tts1/README.md#faq)


# INITIAL RESULTS

## Environments

- date: `Sun Sep 20 19:04:37 JST 2020`
- python version: `3.7.3 (default, Mar 27 2019, 22:11:17)  [GCC 7.3.0]`
- espnet version: `espnet 0.9.3`
- pytorch version: `pytorch 1.6.0`
- Git hash: `08b981aa61e6d4fc951af851f0fa4ebb14f00d4c`
  - Commit date: `Sun Sep 20 02:21:47 2020 +0000`

## Pretrained Models

### vctk_tts_train_gst_tacotron2_raw_phn_tacotron_g2p_en_no_space_train.loss.best
- https://zenodo.org/record/3986237

### vctk_tts_train_gst_fastspeech_raw_phn_tacotron_g2p_en_no_space_train.loss.best
- https://zenodo.org/record/3986241

### vctk_tts_train_gst_transformer_raw_phn_tacotron_g2p_en_no_space_train.loss.ave
- https://zenodo.org/record/4037456

### vctk_tts_train_gst_fastspeech2_raw_phn_tacotron_g2p_en_no_space_train.loss.ave
- https://zenodo.org/record/4036266

### vctk_tts_train_gst_conformer_fastspeech2_raw_phn_tacotron_g2p_en_no_space_train.loss.ave
- https://zenodo.org/record/4036264
