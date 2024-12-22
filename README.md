# Local AI assistant for Engineering Managers

## Description
The ultimate goal of this is an AI assistant that helps engineering managers be more productive with their daily tasks by leveraging best practices from the industry and context of their company.

## Environment setup

### Restore Conda environment:
```bash
conda create --name sora-em --file conda_packages.txt
conda activate sora-em
conda install pip
pip install -r requirements.txt
```

### Extract Conda environment:

```bash
conda list --export > environment.txt
pip freeze | grep -v 'file://' > requirements.txt
```

## Milestones

### Week 1: Team recognition
1. Come up with team recognition of a project achievement


