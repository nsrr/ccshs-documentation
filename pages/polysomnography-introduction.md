# Polysomnography introduction

The polysomnography recording (Compumedics E-series; Compumedics, Abbotsford, Australia) consisted of the following: two electroencephalograms (C3/C2 and C4/C1), bilateral electrooculograms, a bipolar submental electromyogram, thoracic and abdominal respiratory inductance plethysmography (Compumedics Summit IP), airflow (by a Protec nasal–oral thermocouple [Protec, Wordsville, WA] and nasal pressure recording), finger pulse oximetry (Nonin model 320 pulse oximeter [Nonin Medical, Plymouth, MA] with displayed waveform), electrocardiogram, body position, and monitoring bilateral leg movements by piezoelectric sensors.Nocturnal recordings were transmitted to the centralized reading center at Brigham and Women's Hospital and data were scored by trained technicians using current guidelines.

Notes:

- [CCSHS TREC Visit PSG Lab Visit Manual](:files_path:/documentation?f=CCSHS_TREC_Visit_PSG_Lab_Visit_Manual.pdf)
- [CCSHS Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)

## Signal and annotation files

[Raw polysomnography data](:files_path:/polysomnography) are available for 515 Cleveland Children's Sleep and Health Study participants. Each recording has a signal file (.EDF) and two versions of the event scoring and epoch staging annotations (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from Compumedics Profusion.
2. **[XML (Profusion)](:files_path:/polysomnography/annotations-events-profusion)** - Annotation files exported from Compumedics Profusion. ([Learn more...](https://github.com/nsrr/edf-editor-translator/wiki/Compumedics-Annotation-Format))
3. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/community/tools/12) tool.

NSRR XML files can be overlaid onto EDF signal files using the [EDF Viewer tool](https://sleepdata.org/community/tools/nsrr-edf-viewer). For more information about the XML translation (mapping) process, review the files available on the [EDF Editor and Translator Releases page](https://github.com/nsrr/edf-editor-translator/releases).

**Note:** Events using the `Unsure` tag are hypopneas with a >50% decrease in flow (AASM alternative definition).

## History / changelog

*August 2015*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
