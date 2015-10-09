#In-progress Notch8 JS + Angular style guide
###mostly a subset of https://github.com/johnpapa/angular-styleguide

- IIFEs for all code [010](https://github.com/johnpapa/angular-styleguide#style-y010)

- declare controllers, factories, modules with named functions, not anonymous functions [024](https://github.com/johnpapa/angular-styleguide#style-y024)

- controllerAs instead of $scope [030](https://github.com/johnpapa/angular-styleguide#style-y030)

- controllerAs with vm (view-model), because 'this' is confusing and contextually problematic [032](https://github.com/johnpapa/angular-styleguide#style-y032)

- components should reveal their API at the top of the file [052](https://github.com/johnpapa/angular-styleguide#style-y052)
  - function declaration over function expressions because they are order-independent [034](https://github.com/johnpapa/angular-styleguide#style-y034)

- separate data calls (all API interactions) into services [060](https://github.com/johnpapa/angular-styleguide#style-y060)

- return promise from data calls [061](https://github.com/johnpapa/angular-styleguide#style-y061)

- 1 component per file [070](https://github.com/johnpapa/angular-styleguide#style-y070)
  - ie no "directives" folder

- restrict directives to elements [074](https://github.com/johnpapa/angular-styleguide#style-y074)

- use $inject instead of long dependency injection [074](https://github.com/johnpapa/angular-styleguide#style-y074)

###Other stuff not from John Papa:
- camelCase unless it came directly from an API. Please.
- uiRouter instead of Angular router when possible
  - $state.go instead of window.location