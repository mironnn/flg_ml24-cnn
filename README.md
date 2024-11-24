
# Competition #

## Setup ##

```bash
python3.11 -m venv .venv
source ./.venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```

## Kaggle cli ##

```bash
kaggle competitions download -c flg-ml-24-cnn
kaggle competitions submit -c flg-ml-24-cnn -f ./working/submission.csv -m "test submit by API v2"
```
