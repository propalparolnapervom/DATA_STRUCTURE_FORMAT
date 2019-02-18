# README.md

How to handle JSON-format.
  
  - `jq` utility has to be installed


## READ

Show only value of the `name` field

```
cat /tmp/tst.txt 

  {
    "name": "Buster",
    "breed": "Golden Retriever",
    "age": "4",
    "owner": {
      "name": "Sally"
    },
    "likes": [
      "bones",
      "balls",
      "dog biscuits"
    ]
  }


cat /tmp/tst.txt | jq '.name'

  "Buster"
```




















