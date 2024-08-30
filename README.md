1. Set Python Virtual Environment ```python -m venv ENV```
2. Activate Environment ```source ENV/bin/activate``` (for window ```ENV\Scripts\activate```)
3. Install Poetry ```curl -sSL https://install.python-poetry.org | python3 -```
4. Create `pyproject.toml`
```
[tool.poetry]
name = "data-engineering-lifecycle"
version = "0.1.0"
description = ""
authors = ["zkan <zkan.cs@gmail.com>"]

[tool.poetry.dependencies]
python = "^3.10"
requests = "^2.31.0"

[tool.poetry.dev-dependencies]

[build-system]
requires = ["poetry-core>=1.0.0"]
build-backend = "poetry.core.masonry.api"
```
5. Run ```poetry install```
6. Run ```poetry run python main.py```


![image](https://github.com/user-attachments/assets/8ad1f614-658c-4b79-bec3-b47116c34e88)
