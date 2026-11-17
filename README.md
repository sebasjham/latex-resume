# 📋 Resume

## 🤖 Deployment
Deployment is automated by GitHub Actions.

  | Artifact               | Link                                                                          | Mirror                                         |
  | ---------------------- | ----------------------------------------------------------------------------- | ---------------------------------------------- |
  | Résumé                 | <https://sebasjham.github.io/latex-resume/resume.html>                               | <https://sebasjham.github.io/latex-resume/>           |
  | Résumé, Embedded       | <https://sebasjham.github.io/latex-resume/resume-embed.html>                         | <https://sebasjham.github.io/latex-resume/embed.html> |
  | Résumé, Download       | <https://github.com/sebasjham/latex-resume/releases/download/latest/resume.pdf>      |                                                |
- Manually pushed [releases](https://github.com/sebasjham/latex-resume/releases) also trigger workflows to upload artifacts.

# 🔧 Building
## Dependencies
- [TeXLive, full](https://www.tug.org/texlive/)
- [Make](https://www.gnu.org/software/make/)
- [j2cli](https://github.com/kolypto/j2cli)
## Commands
- **Build the résumé**:
  ```bash
  make resume
  ```
- **Build the cirriculum vitae**:
  ```bash
  make cv
  ```
- **Build the cover letter**:
  ```bash
  make coverletter
  ```
- **Build all**:
  ```bash
  make all
  ```
- **Purge all**:
  ```bash
  make clean
  ```
- **Open PDFs**:
  ```bash
  make open
  ```
