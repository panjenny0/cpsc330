## Retrieving rows/columns

### `loc`
Retrieve a slice of columns
`df.loc[:, 'GDP':'population']`
- `:` retrieves all rows
- `'GDP':'population'` retrieves columns from GDP up to and including population

Retrieve a subset of columns
`df.loc[:, ['No.', 'Age', 'Height', 'Weight', 'Experience']]`

### `[]`
Retrieve a single column
`df['Salary']`
