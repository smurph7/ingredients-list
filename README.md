# Ingredients
JSONPlaceholder used to fake data http://jsonplaceholder.typicode.com/

Access the data from https://my-json-server.typicode.com/smurph7/ingredients-list

## Example
```
axios.get(`https://my-json-server.typicode.com/smurph7/ingredients-list/ingredients`)
      .then(res => {
        const ingredients = res.data;
      })
```