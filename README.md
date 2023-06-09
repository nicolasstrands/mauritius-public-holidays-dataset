# Simple Dataset for Public Holidays in Mauritius

## Dataset

### [View Dataset](https://github.com/nicolasstrands/mauritius-public-holidays-dataset/blob/main/data/public-holidays.json)

The aim of this repository and dataset is to provide a hassle-free way to use the data to build applications.

## Disclaimers

- The information from the dataset is provided by the Prime Minister's Office of Mauritius.
- The maintainer of this repository is NOT affiliated with the Prime Minister's Office of Mauritius.
- The data is automatically fetched from the PMO's communiqué but not provided directly by them.
- The page from which the data is fetched is [publicly available](https://pmo.govmu.org/Communique/Public_Holidays_2023.pdf).
- The data is made available here under fair use.

## FAQ

<details>
  <summary>In which format is the data provided?</summary>
  
- JSON
- The data structure is as follows:

```js

{
  "year": [
    {
      "name": string, // "New Year's Day",
      "date": string, // "2023-01-01",
    }
  ]
}
```

</details>
