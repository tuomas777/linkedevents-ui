# Installation

```
$ npm install
$ npm start
```

Then point your browser to the webpack dev server at http://localhost:8080/.

If you're doing API development as well, set your API endpoints in your
local config file at `config/local.yml`, for example:

    api_base: http://localhost:8000/v1
    place_autocomplete_api_base: http://localhost:8000/v1/search/?language=fi&type=place
