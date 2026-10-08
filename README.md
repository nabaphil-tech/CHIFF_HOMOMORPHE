# CHIFF_HOMOMORPHE

Prototype expérimental Master 2 : comparaison Paillier, BFV et calcul en clair sur des transactions financières synthétiques.

## Installation (Ubuntu)

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
pytest -q
python finance_he.py --sizes 10 100 --repetitions 2
python finance_he.py --polynomial
```

Les tests cryptographiques doivent être exécutés localement après installation des dépendances. Ne pas utiliser ce prototype avec des données bancaires réelles.
