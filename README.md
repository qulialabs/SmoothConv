# SmoothConv

SmoothConv is a research initiative focused on advancing natural and smooth human–AI conversational interaction.

Our initial release introduces a high-quality, dual-channel dataset of real human–human conversations, designed specifically for modeling conversational turn-taking and interaction flow.

Unlike many existing resources that rely on single-channel recordings or scripted dialogues, SmoothConv provides:

- Dual-channel recordings capturing both speakers independently  
- Naturally occurring, unscripted conversations  
- Precise conversational structure preserved in timing and overlap  

This enables fine-grained research on turn-taking, interruption modeling, response timing, and interaction dynamics.

---

## 🚀 What Makes SmoothConv Different

### 1. Real Dual-Channel Conversations

Most publicly available conversational datasets are:

- Single-channel mixed audio  
- Scripted or read dialogues  
- Artificially constructed conversational scenarios  

SmoothConv instead offers:

- True dual-channel recordings (separate speaker tracks)  
- Naturally occurring conversations  
- Authentic interaction timing and overlap patterns  

This makes it particularly suitable for modeling conversational flow and real-world dialogue coordination.

---

### 2. Human-Curated Fine-Grained Annotations

All data in the initial release is manually annotated with high precision, including:

- Speaker IDs  
- Accurate timestamps  
- Turn segmentation  
- Paralinguistic signals (e.g., pauses, overlaps, backchannels)  

The dataset is designed for reproducible research and structured modeling of interaction dynamics.

---

## 📦 Initial Release

The first public release includes:

- Annotated dual-channel conversational audio  
- Structured metadata for reproducible training  
- Detailed annotation schema and documentation  
- Standard experimental splits  

---

## 🔜 Upcoming Releases

SmoothConv will progressively expand to include:

- Larger-scale conversational datasets  
- Richer side annotations and interaction cues  
- Benchmark tasks for interaction modeling  
- Baseline and reference models  

Our long-term goal is to provide foundational resources for natural and adaptive human–AI interaction systems.

---

## 📂 Repository Structure

metadata/        # Manifest files and dataset splits  
docs/            # Annotation guidelines and documentation  
sample/          # Sample data for quick inspection  

---

## 📜 License

This dataset is released under the Creative Commons Attribution 4.0 International (CC-BY 4.0) License.

For more details: https://creativecommons.org/licenses/by/4.0/

---

## 📖 Citation

If you use SmoothConv in your research, please cite:

@misc{smoothconv,
  author = {qulialabs}，title={SmoothConv: Datasets for Smooth Human–AI Conversational Interaction},
  year={2025},publisher = {GitHub},journal = {GitHub repository},howpublished = {https://github.com/qulialabs-ethan/SmoothConv},email = {developer@qulialabs.ai}
}
