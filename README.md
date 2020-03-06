# Laravel Interview Questions & Answers

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|1  | [What is Routing?](#what-is-routing) |
|2  | [How many types of routes are there?](#how-many-types-of-routes-are-there) |
|3  | [What is web php?](#what-is-web-php) |
|4  | [What is api php?](#what-is-api-php) |
|5  | [What is channels php?](#what-is-channels-php) |
|6  | [What is console-php?](#what-is-console-php) |
|2  | [What is Controller?](#what-is-controller) |
|3  | [What are Views?](#what-are-views) |
|4  | [What is a Model?](#what-is-a-model) |
|5  | [What is Request-Response?](#what-is-request-response) |
|6  | [When are Migrations?](#what-are-migrations) |
|7  | [What are Seeders?](#what-are-seeders) |
|8  | [What are Service Providers?](#what-are-service-providers) |
|9  | [What is Middleware?](#what-is-middleware) |
|10 | [What is ORM?](#what-is-orm) |
|11 | [What is Eloquent?](#what-is-eloquent) |
|12 | [What is Query Builder?](#what-is-query-builder)
|13 | [What are Facades?](#what-are-facades) |
|14 | [What is Repository Pattern?](#what-is-repository-pattern) |
|15 | [What is Authentication using Passport CSRF XSRF?](#What-is-Authentication-using-Passport-CSRF-XSRF) |
|16 | [What is Unit testing?](#what-is-unit-testing) |
|17 | [What is Caching?](#what-is-caching) |
|18 | [How to setup Emails?](#how-to-setup-emails) |
|19 | [What are Queues?](#what-are-queues) |
|20 | [What are Jobs?](#what-are-jobs)
|21 | [What are Advanced Eloquent and Query Builder?](#what-are-advanced-eloquent-and-query-builder) |
|22 | [Which is Error management?](#which-is-error-management) |
|23 | [How to create an API?](#how-to-create-an-api) |
|24 | [What are Events?](#what-are-events) |
|25 | [What are Listeners?](#what-are-listeners) |
|26 | [What are Payments and cashier?](#what-are-payments-and-cashier) |
|27 | [What is Test Driven Development?](#what-is-test-driven-development) |
|28 | [What is Package development?](#what-is-package-development) |
|29 | [What are Laravel Scout search and Algolia?](#what-are-laravel-scout-search-and-algolia) |
|30 | [What is Socialite and Auth?](#what-is-socialite-auth) |
|31 | [What is Vue-js?](#what-is-vue-js) |
|32 | [How to connect Laravel with other SQL databases?](#How-to-connect-Laravel-with-other-SQL-databases) |
|33 | [How to connect Laravel with non-SQL databases?](#How-to-connect-Laravel-with-non-SQL-databases) |
|34 | [What is Lumen?](#what-is-lumen) |
|35 | [What is Redis?](#what-is-redis) |
|36 | [What is Memcache?](#what-is-memcache) |
|37 | [What is Horizontal scaling?](#What-is-Horizontal-scaling) |
|38 | [What is Vertical scaling?](#What-is-Vertical-scaling) |
|39 | [What is Single Page Application in Laravel?](#What--Single-Page-Application-in-Laravel) |
|40 | [What are Microservices in Laravel?](#What-are-Microservices-in-Laravel) |
|41 | [What is CSRF and JWT token?](#what-is-CSRF-and-JWT-token) |
|42 | [What is Service Oriented Architecture in Laravel?](#what-is-soa) |
|43 | [What are Validations and custom validations?](#what-are-validators) |
|44 | [What is Composer?](#what-is-composer) |
|45 | [What is Symfony?](#what-is-symfony) |
|46 | [What is Route caching?](#what-is-route-caching) |
|47 | [What are Default packages: Cashier,Envoy,Passport,Scout,Socialite,Horizon?](#default-packages) |
|48 | [What are Named routes?](#what-are-named-routes) |
|49 | [What is Dependency injection in Laravel?](#what-is-dependency-injection) |
|50 | [What are Laravel contracts?](#what-are-contracts) |
|51 | [What is Query log?](#what-is-query-log) |
|52 | [What are Laravel Traits?](#what-are-traits) |
|53 | [What are Bundles in Laravel?](#what-are-Bundles-in-Laravel) |
|54 | [What are System requirements for Laravel?](#system-requirements) |
|55 | [What are Aggregate methods in query builder?](#how-error-boundaries-handled-in-react-v15) |
|56 | [What is Singelton design pattern?](#what-are-the-recommended-ways-for-static-type-checking) |
|57 | [What is Reverse routing?](#what-is-the-use-of-react-dom-package) | 
|58 | [What are Popular composer packages?](#what-is-the-purpose-of-render-method-of-react-dom) |
|59 | [How to get the data from more than 3 table without use join ? Answer: Subquery, union.](#what-is-reactdomserver) |
|60 | [List some artisan commands](#how-to-use-innerhtml-in-react) |
|61 | [What are Sessisons?](#how-to-use-styles-in-react) |
|62 | [What are Cookies?](#how-events-are-different-in-react) |
|63 | [What is Current version of PHP, MySQL, Laravel, MongoDB etc?](#what-will-happen-if-you-use-setstate-in-constructor) |
|64 | [Describe design architecture of an app?](#what-is-the-impact-of-indexes-as-keys) |
|65 | [What are SQL Injections?](#is-it-good-to-use-setstate-in-componentwillmount-method) |
|66 | [How to call static methods?](#what-will-happen-if-you-use-props-in-initial-state) |
|67 | [How to achieve multiple DB hosts?](#how-do-you-conditionally-render-components)
|68 | [What is Abstract class?](#why-we-need-to-be-careful-when-spreading-props-on-dom-elements) |
|69 | [What are Default ports for MySQL, Email, etc?](#how-you-use-decorators-in-react) |
|70 | [Explain Joins](#how-do-you-memoize-a-component) |
|71 | [Explain Unions](#how-you-implement-server-side-rendering-or-ssr) |
|72 | [How mongodb is better than relational databases?](#how-to-enable-production-mode-in-react) |
|73 | [What is  mongodb?](#what-is-cra-and-its-benefits) |
|74 | [What is default session time?](#what-is-the-lifecycle-methods-order-in-mounting) |
|75 | [How to create hooks in Laravel?](#what-are-the-lifecycle-methods-going-to-be-deprecated-in-react-v16) |
|76 | [What is csrf token and xss attack?](#what-is-the-purpose-of-getderivedstatefromprops-lifecycle-method) |
|77 | [Select highest/nth highest salary from DB](#what-is-the-purpose-of-getsnapshotbeforeupdate-lifecycle-method) |
|78 | [Write a join](#do-hooks-replace-render-props-and-higher-order-components) |
|79 | [Write a union](#what-is-the-recommended-way-for-naming-components) |
|80 | [Write a complex query?](#what-is-the-recommended-ordering-of-methods-in-component-class) |
|81 | [What is a switching component?](#what-is-a-switching-component) |
|82 | [What is Difference between PHP 5 and 4?](#why-we-need-to-pass-a-function-to-setstate) |
|83 | [What is the difference among various php versions?](#what-is-strict-mode-in-react) |
|84 | [What is the difference among various mysql versions?](#what-are-react-mixins) |
|85 | [What is the difference among various Laravel versions?](#why-is-ismounted-an-anti-pattern-and-what-is-the-proper-solution) |
|86 | [How to add AWS plugin in PHP?](#what-are-the-pointer-events-supported-in-react) |
|87 | [What are design patterns?](#why-should-component-names-start-with-capital-letter) |
|88 | [What is the difference between GET and POST](#are-custom-dom-attributes-supported-in-react-v16) |
|89 | [Which is fast between GET and POST?](#what-is-the-difference-between-constructor-and-getinitialstate) |
|90 | [Explain 4 basics of OOP](#can-you-force-a-component-to-re-render-without-calling-setstate) |
|91 | [What is diference between abstract class and interface?](#what-is-the-difference-between-super-and-superprops-in-react-using-es6-classes) |
|92 | [What is MVC Framework?](#how-to-loop-inside-jsx) |
|93 | [Create a project with CRUD, one algorithm logic and insert data in db for testing.](#how-do-you-access-props-in-attribute-quotes) |
|94 | [Explain CURL and SOAP?](#what-is-react-proptype-array-with-shape) |
|95 | [In MySql we use many types of engines which one is faster and why?](#how-to-conditionally-apply-class-attributes) |
|96 | [What are Triggers?](#what-is-the-difference-between-react-and-reactdom) |
|97 | [What are Procedures](#why-reactdom-is-separated-from-react) |
|98 | [What are some new feaatures of Laravel X?](#how-to-use-react-label-element) |
|99 | [What are some new features of PHP X?](#how-to-combine-multiple-inline-style-objects) |
|100| [Explain Difference between session and cookies?](#how-to-re-render-the-view-when-the-browser-is-resized)
|101| [Merge 2 arrays with duplicate](#what-is-the-difference-between-setstate-and-replacestate-methods) |
|102| [Find the count of vowel and consonants](#how-to-listen-to-state-changes) |
|103| [Explain AWS Services](#what-is-the-recommended-approach-of-removing-an-array-element-in-react-state) |
|104| [How to do Web scraping?](#is-it-possible-to-use-react-without-rendering-html) |
|105| [Explain require and require once difference](#how-to-pretty-print-json-with-react) |
|106| [Explain include and require diffrence](#why-you-cant-update-props-in-react) |
|107| [Directory structure of Laravel](#how-to-focus-an-input-element-on-page-load) |
|108| [How to install Laravel via composer?](#what-are-the-possible-ways-of-updating-objects-in-state) |
|109| [Which ORM are being used by laravel?](#why-function-is-preferred-over-object-for-setstate) |
|110| [List types of relationships available in Laravel Eloquent?](#how-can-we-find-the-version-of-react-at-runtime-in-the-browser) |
|111| [How to enable maintenance mode in Laravel?](#what-are-the-approaches-to-include-polyfills-in-your-create-react-app) |
|112| [What is the purpose of using dd() function in laravel?](#how-to-use-https-instead-of-http-in-create-react-app) |
|113| [How do you register a Service Provider?](#how-to-avoid-using-relative-path-imports-in-create-react-app) |
|114| [How to add Google Analytics for react-router?](#how-to-add-google-analytics-for-react-router) |
|115| [Helper Functions](#how-to-update-a-component-every-second) |
|116| [What is Fillable Attribute in a Laravel Model?](#how-do-you-apply-vendor-prefixes-to-inline-styles-in-react) |
|117| [What is Guarded Attribute in a Laravel Model?](#how-to-import-and-export-components-using-react-and-es6) |
|118| [What are Closures in Laravel?](#why-react-component-names-must-begin-with-a-capital-letter) |
|119| [How to get Logged in user info in Laravel?](#why-is-a-component-constructor-called-only-once) |
|120| [What is Laravel Elixir?](#how-to-define-constants-in-react) |
|121| [What is Laravel Mix?](#how-to-programmatically-trigger-click-event-in-react) |
|122| [How can you display HTML with Blade in Laravel?](#is-it-possible-to-use-asyncawait-in-plain-react) |
|123| [List out databases that laravel supports?](#what-are-the-common-folder-structures-for-react) |
|124| [How to use custom table in Laravel Model?](#what-are-the-popular-packages-for-animation) |
|125| [How To Use Select Query In Laravel? Eloquent and QB?](#what-is-the-benefit-of-styles-modules) |
|126| [What are Accessors and Mutators in Eloquent and why should you use them?](#what-are-the-popular-react-specific-linters) |
|127| [How do I log an error?](#how-to-make-ajax-call-and-in-which-component-lifecycle-methods-should-i-make-an-ajax-call) |
|128| [What is Monolog library in Laravel?](#what-are-render-props) |
|129| [Exceptions are handled by which class in Laravel?](#what-is-react-router) |
|130| [What is Serialization in Laravel?](#how-react-router-is-different-from-history-library) |
|131| [What is Response in Laravel?](#what-are-the-router-components-of-react-router-v4) |
|132| [What is Response Macros in Laravel?](#what-is-the-purpose-of-push-and-replace-methods-of-history) |
|133| [What is Rate Limiting OR Throttle in Laravel?](#how-do-you-programmatically-navigate-using-react-router-v4) |
|134| [What is Lazy vs Eager Loading in Laravel?](#how-to-get-query-parameters-in-react-router-v4) |
|135| [How to get current environment in Laravel?](#why-you-get-router-may-have-only-one-child-element-warning) |
|136| [How to use custom table in Laravel Model ?](#how-to-pass-params-to-historypush-method-in-react-router-v4) |
|137| [What is Binding?](#how-to-implement-default-or-notfound-page) |
|138| [Explain Binding A Singleton?](#how-to-get-history-on-react-router-v4) |
|139| [Explain Binding Instances?](#how-to-perform-automatic-redirect-after-login) |
|140| [Explain Binding Primitives?](#what-is-react-intl) |
|141| [Explain Contextual Binding and how does it work?](#what-are-the-main-features-of-react-intl) |
|142| [What is Tagging?](#what-are-the-two-ways-of-formatting-in-react-intl) |
|143| [Explain Extending Bindings?](#how-to-use-formattedmessage-as-placeholder-using-react-intl) |
|144| [What is the make Method?](#how-to-access-current-locale-with-react-intl) |
|145| [How to clear cache in Laravel?](#how-to-format-date-using-react-intl) |
|146| [What is CSRF token?](#what-is-shallow-renderer-in-react-testing) |
|147| [How will you explain homestead in Laravel?](#what-is-testrenderer-package-in-react) |
|148| [How can we get the user's IP address in Laravel?](#what-is-the-purpose-of-reacttestutils-package) |
|149| [How will you create a helper file in Laravel?](#what-is-jest) |
|150| [How can we create a record in Laravel using eloquent?](#what-are-the-advantages-of-jest-over-jasmine) |
|151| [How can we get the user's IP address in Laravel?](#give-a-simple-example-of-jest-test-case) |
|152| [What is faker in Laravel?](#what-is-flux) |
|153| [What are active records?](#what-is-redux) |
|154| [What are the difference between insert() and insertGetId() in laravel?](#what-are-the-core-principles-of-redux) |
|155| [Talk about Laravel Vapor Compatibility](#what-are-the-downsides-of-redux-compared-to-flux) |
|156| [What is Semantic Versioning?](#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops) |
|157| [What are Jobs and Middleware?](#can-i-dispatch-an-action-in-reducer) |
|158| [Talk about Laravel User Interface (UI)](#how-to-access-redux-store-outside-a-component) |
|159| [Talk about Eloquent Subquery Enhancements?](#what-are-the-drawbacks-of-mvw-pattern) |
|160| [What are improved Authorization Responses?](#are-there-any-similarities-between-redux-and-rxjs) |
|161| [What are lazy collections?](#how-to-dispatch-an-action-on-load) |
|162| [How to make a constant and use globally?](#how-to-use-connect-from-react-redux) |
|163| [How to remove /public from URL in laravel?](#how-to-reset-state-in-redux) |
|164| [What are the difference between soft delete & delete in Laravel?](#whats-the-purpose-of-at-symbol-in-the-redux-connect-decorator) |
|165| [How we can upload files in laravel?](#what-is-the-difference-between-react-context-and-react-redux) |
|166| [How to create real time sitemap.xml file in Laravel?](#why-are-redux-state-functions-called-reducers) |
|167| [How to use skip() and take() in Laravel Query?](#how-to-make-ajax-request-in-redux) |
|168| [What is tinker in laravel?](#should-i-keep-all-components-state-in-redux-store) |
|169| [What is a REPL?](#what-is-the-proper-way-to-access-redux-store) |
|170| [How to use multiple 'OR' condition in Laravel Query?](#what-is-the-difference-between-component-and-container-in-react-redux) |
|171| [Please write some additional where Clauses in Laravel?](#what-is-the-purpose-of-the-constants-in-redux) |
|172| [How to check column is exists or not in a table using Laravel?](#what-are-the-different-ways-to-write-mapdispatchtoprops) |
|173| [What is eager loading in Laravel?](#what-is-the-use-of-the-ownprops-parameter-in-mapstatetoprops-and-mapdispatchtoprops) |
|174| [How to generate application key in laravel?](#how-to-structure-redux-top-level-directories) |
|175| [What is LTS version of Laravel?](#what-is-redux-saga) |
|176| [How to use GROUP_CONCAT() with JOIN in Laravel?](#what-is-the-mental-model-of-redux-saga) |
|177| [How to extend login expire time in Auth?](#what-are-the-differences-between-call-and-put-in-redux-saga) |
|178| [How to extend a layout file in laravel view?](#what-is-redux-thunk) |
|179| [How do you use yield()?](#what-are-the-differences-between-redux-saga-and-redux-thunk) |
|180| [How to redirect form controller to view file in laravel?](#what-is-redux-devtools) |
|181| [How to get current route name?](#what-are-the-features-of-redux-devtools) |
|182| [What is ACL in laravel?](#what-are-redux-selectors-and-why-to-use-them) |
|183| [How to check Ajax request in Laravel?](#what-is-redux-form) |
|184| [How to check if value is sent in request?](#what-are-the-main-features-of-redux-form) |
|185| [Laravel String Helper functions?](#how-to-add-multiple-middlewares-to-redux) |
|186| [Laravel Array Helper functions?](#how-to-set-initial-state-in-redux) |
|187| [How to exclude a route with parameters from CSRF verification?](#how-relay-is-different-from-redux) |
|188| [What are policies classes?](#what-is-the-difference-between-react-native-and-react) |
|189| [How to rollback last migration?](#how-to-test-react-native-apps) |
|190| [What do you mean by Laravel Dusk?](#how-to-do-logging-in-react-native) |
|191| [Explain Laravel echo](#how-to-debug-your-react-native) |
|192| [What is namespace in Laravel?](#what-is-reselect-and-how-it-works) |
|193| [What is Laravel Forge?](#what-is-flow) |
|194| [State the difference between CodeIgniter and Laravel.](#what-is-the-difference-between-flow-and-proptypes) |
|195| [What is an Observer?](#how-to-use-font-awesome-icons-in-react) |
|196| [What is the use of the bootstrap directory?](#what-is-react-dev-tools) |
|197| [What is the default session timeout duration?](#why-is-devtools-not-loading-in-chrome-for-local-files) |
|198| [Explain API.PHP route](#how-to-use-polymer-in-react) |
|199| [Define hashing in Laravel](#what-are-the-advantages-of-react-over-vuejs) |
|200| [What is Localization?](#what-is-the-difference-between-react-and-angular) |
|201| [Explain the concept of encryption and decryption in Laravel.](#why-react-tab-is-not-showing-up-in-devtools) |
|202| [How to share data with views?](#what-are-styled-components) |
|203| [How to generate a request in Laravel?](#give-an-example-of-styled-components) |
|204| [I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?](#what-is-relay) |
|205| [How to assign a variable value for all view file?](#how-to-use-typescript-in-create-react-app-application) |
|206| [How to make a constant and use globally?](#what-are-the-main-features-of-reselect-library) |
|207| [How to check current installed version of Laravel?](#give-an-example-of-reselect-usage) |
|208| [What does "composer dump-autoload" do?](#what-is-an-action-in-redux) |
|209| [What is Kept in vendor directory of Laravel?](#does-the-statics-object-work-with-es6-classes-in-react) |
|210| [What does PHP compact function do?](#can-redux-only-be-used-with-react) |
|210| [What is APP_KEY used for?](#can-redux-only-be-used-with-react) |
## Core Laravel


    
1. ### What is Routing?

  When a user enters a URL, it gets send to a routes file. Laravel contains a routes.php file where it matches it with the right controller/view.

Below is an example route from `routes/web.php`. You can can call site.exension/foo and it will bring the result.

```
Route::get('foo', function () {
    return 'Hello World';
});
```
   **[⬆ Back to Top](#types-of-routes)**
    
2. ### How many types of routes are there?

There are four types of routes in routes.php file,

    A. web.php 
    
    B. api.php
    
    C. console.php
    
    D. broadcast.php

   **[⬆ Back to Top](#what-is-web-php)**
    
5. ### What is web php?

web.php used for web routes. Like example.com/test

    ```
    Route::get('/test', function () {
        $path = storage_path() . "/app/json/options/docs.json";
        return view('skin/dev-wireframe', array('menu' => json_decode(file_get_contents($path), true)));
    });
    ```
    
    
   **[⬆ Back to Top](#types-of-routes)**
    
6. ### What is api php?

    The place where we write API route for mobile and API usage. Like http://localhost:8080/api/test
    ```
    Route::get('/test', function () {
        $path = storage_path() . "/app/json/options/docs.json";
        return view('skin/dev-wireframe', array('menu' => json_decode(file_get_contents($path), true)));
    });
    ```
    
7. ### What is channels php?

...

 **[⬆ Back to Top](#what-is-api-php)**

8. ### What is console php?

Update here.

   **[⬆ Back to Top](#what-is-api-php)**
   
    
6. ### What is Controller?

    Controller is the place where we write the logic of the program. Placed in app/Http/Conrollers

    ```
    <?php namespace App\Http\Controllers;

    use App\Http\Controllers\Controller;

    class UserController extends Controller {

        /**
         * Show the profile for the given user.
         *
         * @param  int  $id
         * @return Response
         */
        public function showProfile($id)
        {
            return view('user.profile', ['user' => User::findOrFail($id)]);
        }

    }
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
3. ### What are Views?

  Views is the fornt end of Laravel. Stored in `resources/views`.

    ```
    <html>
        <body>
            <h1>Hello, {{ $name }}</h1>
        </body>
    </html>
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
4. ### 	What is a Model?
    A model is where you write the database logic. Stored in `/app`

    <?php

    namespace App;

    use Illuminate\Database\Eloquent\Model;

    class Flight extends Model
    {
        //
    }

   **[⬆ Back to Top](#table-of-contents)**
    
5. ### What is Request-Response?

    When we type a URL, a request is sent to the server. The server goes from /public to bootstrap folder from which is goes to the routes file. The route files sends it the right controller/view.


   **[⬆ Back to Top](#table-of-contents)**
    
6. ### What are Migrations?

Migrations help us keep SQL tables in code. When we have to setup the DB, we just run the migration.


   **[⬆ Back to Top](#table-of-contents)**
    
7. ### What are Service Providers?

  Service providers are responsible for booting and configuration (binding all resources.)


   **[⬆ Back to Top](#table-of-contents)**
    
8. ### What is Middleware?

  Middleware checks for authentication.


   **[⬆ Back to Top](#table-of-contents)**
    
9. ### What is ORM?

    Object oriented and Model based way of DB query


   **[⬆ Back to Top](#table-of-contents)**
    
10. ### What is Eloquent?

    The ORM wrapper Laravel uses is called Eloquent. Every table has a model associated with it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
11. ### What is Query Builder?

   A database wrapper that makes it easy to access DB.

   **[⬆ Back to Top](#table-of-contents)**
    
12. ### What are Facades?

    Facades are used to hide implementation details and complexities from end user making him/her feel like interacting with a black box.

   **[⬆ Back to Top](#table-of-contents)**
    
13. ### What is Repository Pattern?

    Repository pattern is used to create templates where implementation details are left to be implemented in child classes. It helps with further expansion of code and avoid bottlenecks in class updation.

   **[⬆ Back to Top](#table-of-contents)**
    
14. ### What is Authentication using Passport?
    
    Passport provides a better way to create API.

   **[⬆ Back to Top](#table-of-contents)**
    
15. ### What Unit testing?
    Testing every function

   **[⬆ Back to Top](#table-of-contents)**
    
16. ### What is Caching?

    Configured using `config/cache.php`. Used for database caching. Popular ways Redis and Memcache.

   **[⬆ Back to Top](#table-of-contents)**
    
17. ### What is Unit Testing?

    Writing a test for every unit (function or class) you write.

   **[⬆ Back to Top](#table-of-contents)**
   
18. ### How to setup Emails?

    Using PHP's `mail()` function amnd Laravel's `sendmail()` function. You can custoimize it using templates.

  **[⬆ Back to Top](#table-of-contents)**
  
18. ### What are Queues?

    Queue is a line of jobs to be proccessed. You can create multiple queues which is multiple lines of jobs
   **[⬆ Back to Top](#table-of-contents)**
    
19. ### What are Jobs?

    Job is a task being performed in the background.

   **[⬆ Back to Top](#table-of-contents)**
   
   
19. ### How to setup Emails?

   Use Laravel's sendmail() function and create a mail template.

   **[⬆ Back to Top](#table-of-contents)**
    
20. ### What are Advanced Eloquent and Query Builder?

    Complex eloquent queries are called advanced eloquent. Query builder is wrapper for database queries.

   **[⬆ Back to Top](#table-of-contents)**
    
21. ### Which is Error management?

   Error handling is managing `exception` in a Laravel application.

   **[⬆ Back to Top](#table-of-contents)**
    
22. ### How to create an API?

  Use api.php. Link will be x.com/api/slug

   **[⬆ Back to Top](#table-of-contents)**
    
23. ### What are Events?

   You get notified when an action is triggered.

   **[⬆ Back to Top](#table-of-contents)**
    
24. ### What are Listeners?

    Which listen to the events.

   **[⬆ Back to Top](#table-of-contents)**
    
25. ### What are Payments and cashier?

    Payment processing is difficult. Cashier is a package which makes it easy. Its installed using composer.

   **[⬆ Back to Top](#table-of-contents)**
    
26. ### What is Test Driven Development?

    Test is written first and then the function is written.

   **[⬆ Back to Top](#table-of-contents)**
    
27. ### What is Package development?

    Larvel uses composer which gets packages. You can develop your own package and submit.

   **[⬆ Back to Top](#table-of-contents)**
    
28. ### What are Laravel Scout search and Algolia?

   https://laravel.com/docs/5.8/scout

   **[⬆ Back to Top](#table-of-contents)**
    
29. ### Socialie and Auth?

    Socialite is Social login for Laravel.
    Auth is Laravel's authentication.

   **[⬆ Back to Top](#table-of-contents)**
    
30. ### What is Vue-js?

    In easy way to do SPA where you can change state.

   **[⬆ Back to Top](#table-of-contents)**
    
31. ### How to connect Laravel with other SQL databases?

    Go to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
32. ### How to connect Laravel with non-SQL databases?

   Add the entry to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
33. ### What is Lumen?

    Lumen is the lightweight version of Laravel used usually for making microservices.

   **[⬆ Back to Top](#table-of-contents)**
    
34. ### What is Redis?
    
    Key-value database making query faster.

   **[⬆ Back to Top](#table-of-contents)**
    
35. ### What is Memcache?

    Key-value database making query faster.


   **[⬆ Back to Top](#table-of-contents)**
    
36. ### What is Horizontal scaling?

    By adding more servers we scale horizontally.

   **[⬆ Back to Top](#table-of-contents)**
    
37. ###	What is Vertical scaling?

    By increasing the size of the same server we scale vertically.

   **[⬆ Back to Top](#table-of-contents)**
    
38. ### What is Single Page Application in Laravel?

    There is single URL. The assets are loaded once and only content keeps changing using JSON request. Its not great for SEO but there are workarounds to create virtual URL.

   **[⬆ Back to Top](#table-of-contents)**
    
40. ### What are Microservices in Laravel?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other.

   **[⬆ Back to Top](#table-of-contents)**
    
41. ### What is CSRF and JWT token?
    CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.

   **[⬆ Back to Top](#table-of-contents)**
    
42. ### What is Service Oriented Architecture in Laravel?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other. 

   **[⬆ Back to Top](#table-of-contents)**
    
43. ### What are Validations and custom validations?

    Validations are used to make sure input is of the kind function wanted. Custom validators are custom made valiators.

   **[⬆ Back to Top](#table-of-contents)**
    
44. ### What is Composer?
   
    Composer is PHP's package manager.

   **[⬆ Back to Top](#table-of-contents)**
    
45. ### What is Symfony?
    Symfony is a framework Laravel is inspired from.

   **[⬆ Back to Top](#table-of-contents)**
    
46. ### What is Route caching?

    Caching of routes to make going to routes faster. Command: `php artisan route:cache`

   **[⬆ Back to Top](#table-of-contents)**
    
47. ### What are Default packages?
    Cashier, Envoy, Passport, Scout, Socialite, Horizon etc

   **[⬆ Back to Top](#table-of-contents)**
    
48. ### What are Named routes?

    You can give route a name using a parameter.

   **[⬆ Back to Top](#table-of-contents)**
    
49. ### What is Dependency injection in Laravel?

Laravel injects dependencies as function parameters.
Read more: https://medium.com/a-young-devoloper/how-laravel-injects-our-dependencies-14e1b1a044e


   **[⬆ Back to Top](#table-of-contents)**
    
50. ### What are Laravel contracts?

 ...

   **[⬆ Back to Top](#table-of-contents)**
    
51. ### What is Query log?

   You can enable logging queries and Laravel will record the queries which were run.

   **[⬆ Back to Top](#table-of-contents)**
    
52. ### What are Laravel Traits?


   **[⬆ Back to Top](#table-of-contents)**
    
53. ### What are Bundles in Laravel?

    Used for grouping stuff like route groups (CRUD in one line.)

   **[⬆ Back to Top](#table-of-contents)**
    
54. ### What are System requirements for Laravel?

PHP version, MySQL, PHP packages mentioned on Laravel.com, apache server

   **[⬆ Back to Top](#table-of-contents)**
    
55	### What are Aggregate methods in query builder?

    Max, min, sum etc
   ```
   $price = DB::table('orders')->max('price');
   ```
   
   **[⬆ Back to Top](#table-of-contents)**
  
    
56	### What is Singelton design pattern?

    A single object of a class is created throughout the lifecycle.

   **[⬆ Back to Top](#table-of-contents)**
    
57	### What is Reverse routing?

    ...
   **[⬆ Back to Top](#table-of-contents)**
    
58	### What are Popular composer packages?

    Guzzle

   **[⬆ Back to Top](#table-of-contents)**
    
59	### How to get the data from more than 3 table without use join ?

 Answer: Subquery, union.


   **[⬆ Back to Top](#table-of-contents)**
    
60	### List some artisan commands

    ```
    php artisan list
    php artisan make:migrate
    php artisan make:controller
    php artisan make:model
    php artisan config:clear
    php artisan serve
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
61	### What are Sessisons?

Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
62	### What are Cookies?

  Cookies is generalized data.


   **[⬆ Back to Top](#table-of-contents)**
    
63	### What is Current version of PHP, MySQL, Laravel, MongoDB etc?

...

   **[⬆ Back to Top](#table-of-contents)**
    
64	### Describe design architecture of an app?

...
  

   **[⬆ Back to Top](#table-of-contents)**
    
65	### What are SQL Injections?

Its a trick to complete a SQL query by filling a form content and placing query parts inside the form.

   **[⬆ Back to Top](#table-of-contents)**
    
66	### How to call static methods?

    Using ::

   **[⬆ Back to Top](#table-of-contents)**
    
67	### How to achieve multiple DB hosts?

    Define the new DB in env or config/database.php and use it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
68	### What is Abstract class?


    A class which is just a template i.e has no defination but just declaration.


   **[⬆ Back to Top](#table-of-contents)**
    
69	### What are Default ports for MySQL, Email, etc?

http: 80
MYSQL: 3306
Email: 587

   **[⬆ Back to Top](#table-of-contents)**
    
70	### Explain Joins

...

   **[⬆ Back to Top](#table-of-contents)**
    
71	### Explain Unions

...

   **[⬆ Back to Top](#table-of-contents)**
    
72	### How mongodb is better than relational databases?

It is faster and it stores data in JSON form so you can enter multiple types of data without being dependent on the data being consistent in type.

   **[⬆ Back to Top](#table-of-contents)**
    
73	### What is mongodb?

   It is a NO SQL key value based database.


   **[⬆ Back to Top](#table-of-contents)**
    
74	### What is default session time?


   1 hour.


   **[⬆ Back to Top](#table-of-contents)**
    
75	### How to create hooks in Laravel?

    ...


   **[⬆ Back to Top](#table-of-contents)**
    
76	### What is csrf token and xss attack?


   ...


   **[⬆ Back to Top](#table-of-contents)**
    
77	### Select highest/nth highest salary from DB


    ...


   **[⬆ Back to Top](#table-of-contents)**
    
78	### Write a join


...

   **[⬆ Back to Top](#table-of-contents)**
    
79. ### Write a union

...

   **[⬆ Back to Top](#table-of-contents)**
    
80. ### Write a complex query?


   Like a 3 tables joined.


   **[⬆ Back to Top](#table-of-contents)**
    
81. ### What is a switching component?


   ...


   **[⬆ Back to Top](#table-of-contents)**
    
82. ### What is Difference between PHP 5 and 4?

    PHP 5 has OOP.


   **[⬆ Back to Top](#table-of-contents)**
    
83. ### What is the difference among various php versions?

    ...

   **[⬆ Back to Top](#table-of-contents)**
    
85. ### What is the difference among various Laravel versions?


    The primary use case for `isMounted()` is to avoid calling `setState()` after a component has been unmounted, because it will emit a warning.

    ```javascript
    if (this.isMounted()) {
      this.setState({...})
    }
    ```

    Checking `isMounted()` before calling `setState()` does eliminate the warning, but it also defeats the purpose of the warning. Using `isMounted()` is a code smell because the only reason you would check is because you think you might be holding a reference after the component has unmounted.

    An optimal solution would be to find places where `setState()` might be called after a component has unmounted, and fix them. Such situations most commonly occur due to callbacks, when a component is waiting for some data and gets unmounted before the data arrives. Ideally, any callbacks should be canceled in `componentWillUnmount()`, prior to unmounting.


   **[⬆ Back to Top](#table-of-contents)**
    
86. ### How to add AWS plugin in PHP?


    *Pointer Events* provide a unified way of handling all input events. In the old days we had a mouse and respective event listeners to handle them but nowadays we have many devices which don't correlate to having a mouse, like phones with touch surface or pens. We need to remember that these events will only work in browsers that support the *Pointer Events* specification.

    The following event types are now available in *React DOM*:

    1. `onPointerDown`
    2. `onPointerMove`
    3. `onPointerUp`
    4. `onPointerCancel`
    5. `onGotPointerCapture`
    6. `onLostPointerCaptur`
    7. `onPointerEnter`
    8. `onPointerLeave`
    9. `onPointerOver`
    10. `onPointerOut`


   **[⬆ Back to Top](#table-of-contents)**
    
87. ### What are design patterns?


    If you are rendering your component using JSX, the name of that component has to begin with a capital letter otherwise React will throw an error as unrecognized tag. This convention is because only HTML elements and SVG tags can begin with a lowercase letter.
    ```jsx harmony
    class SomeComponent extends Component {
     // Code goes here
    }
    ```
    You can define component class which name starts with lowercase letter, but when it's imported it should have capital letter. Here lowercase is fine:

    ```jsx harmony
    class myComponent extends Component {
      render() {
        return <div />
      }
    }

    export default myComponent
    ```

    While when imported in another file it should start with capital letter:

    ```jsx harmony
    import MyComponent from './MyComponent'
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
88. ### What is the difference between GET and POST


    Yes. In the past, React used to ignore unknown DOM attributes. If you wrote JSX with an attribute that React doesn't recognize, React would just skip it. For example, this:

    ```jsx harmony
    <div mycustomattribute={'something'} />
    ```

    Would render an empty div to the DOM with React v15:

    ```html
    <div />
    ```

    In React v16 any unknown attributes will end up in the DOM:

    ```html
    <div mycustomattribute='something' />
    ```

    This is useful for supplying browser-specific non-standard attributes, trying new DOM APIs, and integrating with opinionated third-party libraries.


   **[⬆ Back to Top](#table-of-contents)**
    
89. ### Which is fast between GET and POST?


    You should initialize state in the constructor when using ES6 classes, and `getInitialState()` method when using `React.createClass()`.

    Using ES6 classes:

    ```javascript
    class MyComponent extends React.Component {
      constructor(props) {
        super(props)
        this.state = { /* initial state */ }
      }
    }
    ```

    Using `React.createClass()`:

    ```javascript
    const MyComponent = React.createClass({
      getInitialState() {
        return { /* initial state */ }
      }
    })
    ```

    **Note:** `React.createClass()` is deprecated and removed in React v16. Use plain JavaScript classes instead.


   **[⬆ Back to Top](#table-of-contents)**
    
90. ### Explain 4 basics of OOP


    By default, when your component's state or props change, your component will re-render. If your `render()` method depends on some other data, you can tell React that the component needs re-rendering by calling `forceUpdate()`.

    ```javascript
    component.forceUpdate(callback)
    ```

    It is recommended to avoid all uses of `forceUpdate()` and only read from `this.props` and `this.state` in `render()`.


   **[⬆ Back to Top](#table-of-contents)**
    
91. ### What is diference between abstract class and interface?


    When you want to access `this.props` in `constructor()` then you should pass props to `super()` method.

    Using `super(props)`:

    ```javascript
    class MyComponent extends React.Component {
      constructor(props) {
        super(props)
        console.log(this.props) // { name: 'John', ... }
      }
    }
    ```

    Using `super()`:

    ```javascript
    class MyComponent extends React.Component {
      constructor(props) {
        super()
        console.log(this.props) // undefined
      }
    }
    ```

    Outside `constructor()` both will display same value for `this.props`.


   **[⬆ Back to Top](#table-of-contents)**
    
92. ### What is MVC Framework?


    You can simply use `Array.prototype.map` with ES6 *arrow function* syntax. For example, the `items` array of objects is mapped into an array of components:

    ```jsx harmony
    <tbody>
      {items.map(item => <SomeComponent key={item.id} name={item.name} />)}
    </tbody>
    ```

    You can't iterate using `for` loop:

    ```jsx harmony
    <tbody>
      for (let i = 0; i < items.length; i++) {
        <SomeComponent key={items[i].id} name={items[i].name} />
      }
    </tbody>
    ```

    This is because JSX tags are transpiled into *function calls*, and you can't use statements inside expressions. This may change thanks to `do` expressions which are *stage 1 proposal*.


   **[⬆ Back to Top](#table-of-contents)**
    
93. ### Create a project with CRUD, one algorithm logic and insert data in db for testing.




   **[⬆ Back to Top](#table-of-contents)**
    
95. ### In MySql we use many types of engines which one is faster and why?

There are two main types of engines,
1.InnoDB
2.MyISAM
InnoDB is faster.

   **[⬆ Back to Top](#table-of-contents)**
    
96. ### What are Triggers?


...


   **[⬆ Back to Top](#table-of-contents)**
    
97. ### What are Procedures

...

   **[⬆ Back to Top](#table-of-contents)**
    
98. ### What are some new feaatures of Laravel X?

...

   **[⬆ Back to Top](#table-of-contents)**
    
99. ### What are some new features of PHP X?

PHP 7.4 brings,
1. 
2.


   **[⬆ Back to Top](#table-of-contents)**
    
100. ### Explain Difference between session and cookies?

  Cookies is data sent with every request. It is usually generalized for all.
  Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
101. ### Merge 2 arrays with duplicate


     When you use `setState()` the current and previous states are merged. `replaceState()` throws out the current state, and replaces it with only what you provide. Usually `setState()` is used unless you really need to remove all previous keys for some reason. You can also set state to `false`/`null` in `setState()` instead of using `replaceState()`.


   **[⬆ Back to Top](#table-of-contents)**
    
102. ### Find the count of vowel and consonants


     The following lifecycle methods will be called when state changes. You can compare provided state and props values with current state and props to determine if something meaningful changed.

     ```
     componentWillUpdate(object nextProps, object nextState)
     componentDidUpdate(object prevProps, object prevState)
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
103. ### Explain AWS Services


     The better approach is to use `Array.prototype.filter()` method.

     For example, let's create a `removeItem()` method for updating the state.

     ```javascript
     removeItem(index) {
       this.setState({
         data: this.state.data.filter((item, i) => i !== index)
       })
     }
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
104. ### How to do Web scraping?


     It is possible with latest version (>=16.2). Below are the possible options:

     ```jsx harmony
     render() {
       return false
     }
     ```

     ```jsx harmony
     render() {
       return null
     }
     ```

     ```jsx harmony
     render() {
       return []
     }
     ```

     ```jsx harmony
     render() {
       return <React.Fragment></React.Fragment>
     }
     ```

     ```jsx harmony
     render() {
       return <></>
     }
     ```

     Returning `undefined` won't work.


   **[⬆ Back to Top](#table-of-contents)**
    
105. ### Explain require and require once difference


     We can use `<pre>` tag so that the formatting of the `JSON.stringify()` is retained:

     ```jsx harmony
     const data = { name: 'John', age: 42 }

     class User extends React.Component {
       render() {
         return (
           <pre>
             {JSON.stringify(data, null, 2)}
           </pre>
         )
       }
     }

     React.render(<User />, document.getElementById('container'))
     ```


   **[⬆ Back to Top](#table-of-contents)**
   
106. ### Explain include and require diffrence


     The React philosophy is that props should be *immutable* and *top-down*. This means that a parent can send any prop values to a child, but the child can't modify received props.


   **[⬆ Back to Top](#table-of-contents)**
    
107. ### Directory structure of Laravel


     You can do it by creating *ref* for `input` element and using it in `componentDidMount()`:

     ```jsx harmony
     class App extends React.Component{
       componentDidMount() {
         this.nameInput.focus()
       }

       render() {
         return (
           <div>
             <input
               defaultValue={'Won\'t focus'}
             />
             <input
               ref={(input) => this.nameInput = input}
               defaultValue={'Will focus'}
             />
           </div>
         )
       }
     }

     ReactDOM.render(<App />, document.getElementById('app'))
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
108. ### How to install Laravel via composer?


     1. **Calling `setState()` with an object to merge with state:**

         * Using `Object.assign()` to create a copy of the object:

             ```javascript
             const user = Object.assign({}, this.state.user, { age: 42 })
             this.setState({ user })
             ```

         * Using *spread operator*:

             ```javascript
             const user = { ...this.state.user, age: 42 }
             this.setState({ user })
             ```

     2. **Calling `setState()` with a function:**

         ```javascript
         this.setState(prevState => ({
           user: {
             ...prevState.user,
             age: 42
           }
         }))
         ```


   **[⬆ Back to Top](#table-of-contents)**
    
109. ### Which ORM are being used by laravel?


     React may batch multiple `setState()` calls into a single update for performance. Because `this.props` and `this.state` may be updated asynchronously, you should not rely on their values for calculating the next state.

     This counter example will fail to update as expected:

     ```javascript
     // Wrong
     this.setState({
       counter: this.state.counter + this.props.increment,
     })
     ```

     The preferred approach is to call `setState()` with function rather than object. That function will receive the previous state as the first argument, and the props at the time the update is applied as the second argument.

     ```javascript
     // Correct
     this.setState((prevState, props) => ({
       counter: prevState.counter + props.increment
     }))
     ```


   **[⬆ Back to Top](#table-of-contents)**
   
110. ### List types of relationships available in Laravel Eloquent?


     You can use `React.version` to get the version.

     ```jsx harmony
     const REACT_VERSION = React.version

     ReactDOM.render(
       <div>{`React version: ${REACT_VERSION}`}</div>,
       document.getElementById('app')
     )
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
111. ### How to enable maintenance mode in Laravel?


     1. **Manual import from `core-js`:**

         Create a file called (something like) `polyfills.js` and import it into root `index.js` file. Run `npm install core-js` or `yarn add core-js` and import your specific required features.

         ```javascript
         import 'core-js/fn/array/find'
         import 'core-js/fn/array/includes'
         import 'core-js/fn/number/is-nan'
         ```

     2. **Using Polyfill service:**

         Use the polyfill.io CDN to retrieve custom, browser-specific polyfills by adding this line to `index.html`:

         ```html
         <script src='https://cdn.polyfill.io/v2/polyfill.min.js?features=default,Array.prototype.includes'></script>
         ```

         In the above script we had to explicitly request the `Array.prototype.includes` feature as it is not included in the default feature set.


   **[⬆ Back to Top](#table-of-contents)**
    
112. ### What is the purpose of using dd() function in laravel?


     You just need to use `HTTPS=true` configuration. You can edit your `package.json` scripts section:

     ```json
     "scripts": {
       "start": "set HTTPS=true && react-scripts start"
     }
     ```

     or just run `set HTTPS=true && npm start`


   **[⬆ Back to Top](#table-of-contents)**
    
113. ### How do you register a Service Provider?


     Create a file called `.env` in the project root and write the import path:

     ```
     NODE_PATH=src/app
     ```

     After that restart the development server. Now you should be able to import anything inside `src/app` without relative paths.


   **[⬆ Back to Top](#table-of-contents)**
    
114. ### How to add Google Analytics for react-router?


     Add a listener on the `history` object to record each page view:

     ```javascript
     history.listen(function (location) {
       window.ga('set', 'page', location.pathname + location.search)
       window.ga('send', 'pageview', location.pathname + location.search)
     })
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
115. ### Helper Functions


     You need to use `setInterval()` to trigger the change, but you also need to clear the timer when the component unmounts to prevent errors and memory leaks.

     ```javascript
     componentDidMount() {
       this.interval = setInterval(() => this.setState({ time: Date.now() }), 1000)
     }

     componentWillUnmount() {
       clearInterval(this.interval)
     }
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
116. ### What is Fillable Attribute in a Laravel Model?


     React *does not* apply *vendor prefixes* automatically. You need to add vendor prefixes manually.

     ```jsx harmony
     <div style={{
       transform: 'rotate(90deg)',
       WebkitTransform: 'rotate(90deg)', // note the capital 'W' here
       msTransform: 'rotate(90deg)' // 'ms' is the only lowercase vendor prefix
     }} />
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
117. ### What is Guarded Attribute in a Laravel Model?


     You should use default for exporting the components

     ```jsx harmony
     import React from 'react'
     import User from 'user'

     export default class MyProfile extends React.Component {
       render(){
         return (
           <User type="customer">
             //...
           </User>
         )
       }
     }
     ```

     With the export specifier, the MyProfile is going to be the member and exported to this module and the same can be imported without mentioning the name in other components.


   **[⬆ Back to Top](#table-of-contents)**
    
118. ### What are Closures in Laravel?


     The component names should start with a uppercase letter but there are few exceptions on this convention. The lowercase tag names with a dot (property accessors) are still considered as valid component names.
     For example the below tag can be compiled to a valid component,
     ```javascript
     render(){
        return (
            <obj.component /> // `React.createElement(obj.component)`
           )
     }
     ```

   **[⬆ Back to Top](#table-of-contents)**
    
119. ### How to get Logged in user info in Laravel?


     React's *reconciliation* algorithm assumes that without any information to the contrary, if a custom component appears in the same place on subsequent renders, it's the same component as before, so reuses the previous instance rather than creating a new one.


   **[⬆ Back to Top](#table-of-contents)**
    
120. ### What is Laravel Elixir?


     You can use ES7 `static` field to define constant.

     ```javascript
     class MyComponent extends React.Component {
       static DEFAULT_PAGINATION = 10
     }
     ```

     *Static fields* are part of the *Class Fields* stage 3 proposal.


   **[⬆ Back to Top](#table-of-contents)**
    
121. ### What is Laravel Mix?


     You could use the ref prop to acquire a reference to the underlying `HTMLInputElement` object through a callback, store the reference as a class property, then use that reference to later trigger a click from your event handlers using the `HTMLElement.click` method. This can be done in two steps:

     1. Create ref in render method:

         ```jsx harmony
         <input ref={input => this.inputElement = input} />
         ```

     2. Apply click event in your event handler:

         ```javascript
         this.inputElement.click()
         ```


   **[⬆ Back to Top](#table-of-contents)**
    
122. ### How can you display HTML with Blade in Laravel?


     If you want to use `async`/`await` in React, you will need *Babel* and [transform-async-to-generator](https://babeljs.io/docs/en/babel-plugin-transform-async-to-generator) plugin. React Native ships with Babel and a set of transforms.


   **[⬆ Back to Top](#table-of-contents)**
    
123. ### What are the common folder structures for React?

     There are two common practices for React project file structure.

     1. **Grouping by features or routes:**

         One common way to structure projects is locate CSS, JS, and tests together, grouped by feature or route.

         ```
         common/
         ├─ Avatar.js
         ├─ Avatar.css
         ├─ APIUtils.js
         └─ APIUtils.test.js
         feed/
         ├─ index.js
         ├─ Feed.js
         ├─ Feed.css
         ├─ FeedStory.js
         ├─ FeedStory.test.js
         └─ FeedAPI.js
         profile/
         ├─ index.js
         ├─ Profile.js
         ├─ ProfileHeader.js
         ├─ ProfileHeader.css
         └─ ProfileAPI.js
         ```

     2. **Grouping by file type:**

         Another popular way to structure projects is to group similar files together.

         ```
         api/
         ├─ APIUtils.js
         ├─ APIUtils.test.js
         ├─ ProfileAPI.js
         └─ UserAPI.js
         components/
         ├─ Avatar.js
         ├─ Avatar.css
         ├─ Feed.js
         ├─ Feed.css
         ├─ FeedStory.js
         ├─ FeedStory.test.js
         ├─ Profile.js
         ├─ ProfileHeader.js
         └─ ProfileHeader.css
         ```


   **[⬆ Back to Top](#table-of-contents)**
    
124. ### List out databases that laravel supports?


     *React Transition Group* and *React Motion* are popular animation packages in React ecosystem.


   **[⬆ Back to Top](#table-of-contents)**
    
124. ### How to use custom table in Laravel Model?


     It is recommended to avoid hard coding style values in components. Any values that are likely to be used across different UI components should be extracted into their own modules.

     For example, these styles could be extracted into a separate component:

     ```javascript
     export const colors = {
       white,
       black,
       blue
     }

     export const space = [
       0,
       8,
       16,
       32,
       64
     ]
     ```

     And then imported individually in other components:

     ```javascript
     import { space, colors } from './styles'
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
125. ### How To Use Select Query In Laravel? Eloquent and QB?

126. ### What are Accessors and Mutators in Eloquent and why should you use them?


     ESLint is a popular JavaScript linter. There are plugins available that analyse specific code styles. One of the most common for React is an npm package called `eslint-plugin-react`. By default, it will check a number of best practices, with rules checking things from keys in iterators to a complete set of prop types. Another popular plugin is `eslint-plugin-jsx-a11y`, which will help fix common issues with accessibility. As JSX offers slightly different syntax to regular HTML, issues with `alt` text and `tabindex`, for example, will not be picked up by regular plugins.


   **[⬆ Back to Top](#table-of-contents)**
    
127. ### How do I log an error?


     You can use AJAX libraries such as Axios, jQuery AJAX, and the browser built-in `fetch`. You should fetch data in the `componentDidMount()` lifecycle method. This is so you can use `setState()` to update your component when the data is retrieved.

     For example, the employees list fetched from API and set local state:

     ```jsx harmony
     class MyComponent extends React.Component {
       constructor(props) {
         super(props)
         this.state = {
           employees: [],
           error: null
         }
       }

       componentDidMount() {
         fetch('https://api.example.com/items')
           .then(res => res.json())
           .then(
             (result) => {
               this.setState({
                 employees: result.employees
               })
             },
             (error) => {
               this.setState({ error })
             }
           )
       }

       render() {
         const { error, employees } = this.state
         if (error) {
           return <div>Error: {error.message}</div>;
         } else {
           return (
             <ul>
               {employees.map(item => (
                 <li key={employee.name}>
                   {employee.name}-{employees.experience}
                 </li>
               ))}
             </ul>
           )
         }
       }
     }
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
128. ### What is Monolog library in Laravel?


     **Render Props** is a simple technique for sharing code between components using a prop whose value is a function. The below component uses render prop which returns a React element.

     ```jsx harmony
     <DataProvider render={data => (
       <h1>{`Hello ${data.target}`}</h1>
     )}/>
     ```

     Libraries such as React Router and DownShift are using this pattern.

## React Router


   **[⬆ Back to Top](#table-of-contents)**
    
129. ### Exceptions are handled by which class in Laravel?


     React Router is a powerful routing library built on top of React that helps you add new screens and flows to your application incredibly quickly, all while keeping the URL in sync with what's being displayed on the page.


   **[⬆ Back to Top](#table-of-contents)**
    
130. ### What is Serialization in Laravel?


     React Router is a wrapper around the `history` library which handles interaction with the browser's `window.history` with its browser and hash histories. It also provides memory history which is useful for environments that don't have global history, such as mobile app development (React Native) and unit testing with Node.


   **[⬆ Back to Top](#table-of-contents)**
    
131. ### What is Response in Laravel?


     React Router v4 provides below 3 `<Router>` components:

     1. `<BrowserRouter>`
     2. `<HashRouter>`
     3. `<MemoryRouter>`

     The above components will create *browser*, *hash*, and *memory* history instances. React Router v4 makes the properties and methods of the `history` instance associated with your router available through the context in the `router` object.


   **[⬆ Back to Top](#table-of-contents)**
    
132. ### What is Response Macros in Laravel?


     A history instance has two methods for navigation purpose.

     1. `push()`
     2. `replace()`

     If you think of the history as an array of visited locations, `push()` will add a new location to the array and `replace()` will replace the current location in the array with the new one.


   **[⬆ Back to Top](#table-of-contents)**
    
133. ### What is Rate Limiting OR Throttle in Laravel?


     There are three different ways to achieve programmatic routing/navigation within components.

     1. **Using the `withRouter()` higher-order function:**

         The `withRouter()` higher-order function will inject the history object as a prop of the component. This object provides `push()` and `replace()` methods to avoid the usage of context.

         ```jsx harmony
         import { withRouter } from 'react-router-dom' // this also works with 'react-router-native'

         const Button = withRouter(({ history }) => (
           <button
             type='button'
             onClick={() => { history.push('/new-location') }}
           >
             {'Click Me!'}
           </button>
         ))
         ```

     2. **Using `<Route>` component and render props pattern:**

         The `<Route>` component passes the same props as `withRouter()`, so you will be able to access the history methods through the history prop.

         ```jsx harmony
         import { Route } from 'react-router-dom'

         const Button = () => (
           <Route render={({ history }) => (
             <button
               type='button'
               onClick={() => { history.push('/new-location') }}
             >
               {'Click Me!'}
             </button>
           )} />
         )
         ```

     3. **Using context:**

         This option is not recommended and treated as unstable API.

         ```jsx harmony
         const Button = (props, context) => (
           <button
             type='button'
             onClick={() => {
               context.history.push('/new-location')
             }}
           >
             {'Click Me!'}
           </button>
         )

         Button.contextTypes = {
           history: React.PropTypes.shape({
             push: React.PropTypes.func.isRequired
           })
         }
         ```


   **[⬆ Back to Top](#table-of-contents)**
    
134. ### What is Lazy vs Eager Loading in Laravel?


     The ability to parse query strings was taken out of React Router v4 because there have been user requests over the years to support different implementation. So the decision has been given to users to choose the implementation they like. The recommended approach is to use query strings library.

     ```javascript
     const queryString = require('query-string');
     const parsed = queryString.parse(props.location.search);
     ```

     You can also use `URLSearchParams` if you want something native:

     ```javascript
     const params = new URLSearchParams(props.location.search)
     const foo = params.get('name')
     ```

     You should use a *polyfill* for IE11.


   **[⬆ Back to Top](#table-of-contents)**
    
135. ### How to get current environment in Laravel?


     You have to wrap your Route's in a `<Switch>` block because `<Switch>` is unique in that it renders a route exclusively.

     At first you need to add `Switch` to your imports:

     ```javascript
     import { Switch, Router, Route } from 'react-router'
     ```

     Then define the routes within `<Switch>` block:

     ```jsx harmony
     <Router>
       <Switch>
         <Route {/* ... */} />
         <Route {/* ... */} />
       </Switch>
     </Router>
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
136. ### How to use custom table in Laravel Model ?


     While navigating you can pass props to the `history` object:

     ```javascript
     this.props.history.push({
       pathname: '/template',
       search: '?name=sudheer',
       state: { detail: response.data }
     })
     ```

     The `search` property is used to pass query params in `push()` method.


   **[⬆ Back to Top](#table-of-contents)**
    
137. ### What is Binding?


     A `<Switch>` renders the first child `<Route>` that matches. A `<Route>` with no path always matches. So you just need to simply drop path attribute as below

     ```jsx harmony
     <Switch>
       <Route exact path="/" component={Home}/>
       <Route path="/user" component={User}/>
       <Route component={NotFound} />
     </Switch>
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
138. ### Explain Binding A Singleton?


     1. Create a module that exports a `history` object and import this module across the project.

         For example, create `history.js` file:

         ```javascript
         import { createBrowserHistory } from 'history'

         export default createBrowserHistory({
           /* pass a configuration object here if needed */
         })
         ```

     2. You should use the `<Router>` component instead of built-in routers. Imported the above `history.js` inside `index.js` file:

         ```jsx harmony
         import { Router } from 'react-router-dom'
         import history from './history'
         import App from './App'

         ReactDOM.render((
           <Router history={history}>
             <App />
           </Router>
         ), holder)
         ```

     3. You can also use push method of `history` object similar to built-in history object:

         ```javascript
         // some-other-file.js
         import history from './history'

         history.push('/go-here')
         ```


   **[⬆ Back to Top](#table-of-contents)**
    
139. ### Explain Binding Instances?


     The `react-router` package provides `<Redirect>` component in React Router. Rendering a `<Redirect>` will navigate to a new location. Like server-side redirects, the new location will override the current location in the history stack.

     ```javascript
     import React, { Component } from 'react'
     import { Redirect } from 'react-router'

     export default class LoginComponent extends Component {
       render() {
         if (this.state.isLoggedIn === true) {
           return <Redirect to="/your/redirect/page" />
         } else {
           return <div>{'Login Please'}</div>
         }
       }
     }
     ```

## React Internationalization


   **[⬆ Back to Top](#table-of-contents)**
    
140. ### Explain Binding Primitives?


     The *React Intl* library makes internalization in React straightforward, with off-the-shelf components and an API that can handle everything from formatting strings, dates, and numbers, to pluralization. React Intl is part of *FormatJS* which provides bindings to React via its components and API.


   **[⬆ Back to Top](#table-of-contents)**
    
141. ### Explain Contextual Binding and how does it work?


     1. Display numbers with separators.
     2. Display dates and times correctly.
     3. Display dates relative to "now".
     4. Pluralize labels in strings.
     5. Support for 150+ languages.
     6. Runs in the browser and Node.
     7. Built on standards.


   **[⬆ Back to Top](#table-of-contents)**
    
142. ### What is Tagging?


     The library provides two ways to format strings, numbers, and dates: react components or an API.

     ```jsx harmony
     <FormattedMessage
       id={'account'}
       defaultMessage={'The amount is less than minimum balance.'}
     />
     ```

     ```javascript
     const messages = defineMessages({
       accountMessage: {
         id: 'account',
         defaultMessage: 'The amount is less than minimum balance.',
       }
     })

     formatMessage(messages.accountMessage)
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
143. ### Explain Extending Bindings?


     The `<Formatted... />` components from `react-intl` return elements, not plain text, so they can't be used for placeholders, alt text, etc. In that case, you should use lower level API `formatMessage()`. You can inject the `intl` object into your component using `injectIntl()` higher-order component and then format the message using `formatMessage()` available on that object.

     ```jsx harmony
     import React from 'react'
     import { injectIntl, intlShape } from 'react-intl'

     const MyComponent = ({ intl }) => {
       const placeholder = intl.formatMessage({id: 'messageId'})
       return <input placeholder={placeholder} />
     }

     MyComponent.propTypes = {
       intl: intlShape.isRequired
     }

     export default injectIntl(MyComponent)
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
144. ### What is the make Method?


     You can get the current locale in any component of your application using `injectIntl()`:

     ```jsx harmony
     import { injectIntl, intlShape } from 'react-intl'

     const MyComponent = ({ intl }) => (
       <div>{`The current locale is ${intl.locale}`}</div>
     )

     MyComponent.propTypes = {
       intl: intlShape.isRequired
     }

     export default injectIntl(MyComponent)
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
145. ### How to clear cache in Laravel?


     The `injectIntl()` higher-order component will give you access to the `formatDate()` method via the props in your component. The method is used internally by instances of `FormattedDate` and it returns the string representation of the formatted date.

     ```jsx harmony
     import { injectIntl, intlShape } from 'react-intl'

     const stringDate = this.props.intl.formatDate(date, {
       year: 'numeric',
       month: 'numeric',
       day: 'numeric'
     })

     const MyComponent = ({intl}) => (
       <div>{`The formatted date is ${stringDate}`}</div>
     )

     MyComponent.propTypes = {
       intl: intlShape.isRequired
     }

     export default injectIntl(MyComponent)
     ```

## React Testing


   **[⬆ Back to Top](#table-of-contents)**
    
146. ### What is CSRF token?


     *Shallow rendering* is useful for writing unit test cases in React. It lets you render a component *one level deep* and assert facts about what its render method returns, without worrying about the behavior of child components, which are not instantiated or rendered.

     For example, if you have the following component:

     ```javascript
     function MyComponent() {
       return (
         <div>
           <span className={'heading'}>{'Title'}</span>
           <span className={'description'}>{'Description'}</span>
         </div>
       )
     }
     ```

     Then you can assert as follows:

     ```jsx harmony
     import ShallowRenderer from 'react-test-renderer/shallow'

     // in your test
     const renderer = new ShallowRenderer()
     renderer.render(<MyComponent />)

     const result = renderer.getRenderOutput()

     expect(result.type).toBe('div')
     expect(result.props.children).toEqual([
       <span className={'heading'}>{'Title'}</span>,
       <span className={'description'}>{'Description'}</span>
     ])
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
147. ### How will you explain homestead in Laravel?


     This package provides a renderer that can be used to render components to pure JavaScript objects, without depending on the DOM or a native mobile environment. This package makes it easy to grab a snapshot of the platform view hierarchy (similar to a DOM tree) rendered by a ReactDOM or React Native without using a browser or `jsdom`.

     ```jsx harmony
     import TestRenderer from 'react-test-renderer'

     const Link = ({page, children}) => <a href={page}>{children}</a>

     const testRenderer = TestRenderer.create(
       <Link page={'https://www.facebook.com/'}>{'Facebook'}</Link>
     )

     console.log(testRenderer.toJSON())
     // {
     //   type: 'a',
     //   props: { href: 'https://www.facebook.com/' },
     //   children: [ 'Facebook' ]
     // }
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
14. ### How can we get the user's IP address in Laravel?


     *ReactTestUtils* are provided in the `with-addons` package and allow you to perform actions against a simulated DOM for the purpose of unit testing.


   **[⬆ Back to Top](#table-of-contents)**
    
149. ### How will you create a helper file in Laravel?

     *Jest* is a JavaScript unit testing framework created by Facebook based on Jasmine and provides automated mock creation and a `jsdom` environment. It's often used for testing components.


   **[⬆ Back to Top](#table-of-contents)**
    
150. ### How can we create a record in Laravel using eloquent?

     There are couple of advantages compared to Jasmine:

     - Automatically finds tests to execute in your source code.
     - Automatically mocks dependencies when running your tests.
     - Allows you to test asynchronous code synchronously.
     - Runs your tests with a fake DOM implementation (via `jsdom`) so that your tests can be run on the command line.
     - Runs tests in parallel processes so that they finish sooner.


   **[⬆ Back to Top](#table-of-contents)**
    

151. ### How can we get the user's IP address in Laravel?

     Let's write a test for a function that adds two numbers in `sum.js` file:

     ```javascript
     const sum = (a, b) => a + b

     export default sum
     ```

     Create a file named `sum.test.js` which contains actual test:

     ```javascript
     import sum from './sum'

     test('adds 1 + 2 to equal 3', () => {
       expect(sum(1, 2)).toBe(3)
     })
     ```

     And then add the following section to your `package.json`:

     ```json
     {
       "scripts": {
         "test": "jest"
       }
     }
     ```

     Finally, run `yarn test` or `npm test` and Jest will print a result:

     ```console
     $ yarn test
     PASS ./sum.test.js
     ✓ adds 1 + 2 to equal 3 (2ms)
     ```

## React Redux


   **[⬆ Back to Top](#table-of-contents)**
    
152. ### What is faker in Laravel?

     *Flux* is an *application design paradigm* used as a replacement for the more traditional MVC pattern. It is not a framework or a library but a new kind of architecture that complements React and the concept of Unidirectional Data Flow. Facebook uses this pattern internally when working with React.

     The workflow between dispatcher, stores and views components with distinct inputs and outputs as follows:

     ![flux](images/flux.png)


   **[⬆ Back to Top](#table-of-contents)**
    
153. ### What are active records?


     *Redux* is a predictable state container for JavaScript apps based on the *Flux design pattern*. Redux can be used together with React, or with any other view library. It is tiny (about 2kB) and has no dependencies.


   **[⬆ Back to Top](#table-of-contents)**
    
154. ### What are the difference between insert() and insertGetId() in laravel?


     Redux follows three fundamental principles:

     1. **Single source of truth:** The state of your whole application is stored in an object tree within a single store. The single state tree makes it easier to keep track of changes over time and debug or inspect the application.
     2. **State is read-only:** The only way to change the state is to emit an action, an object describing what happened. This ensures that neither the views nor the network callbacks will ever write directly to the state.
     3. **Changes are made with pure functions:** To specify how the state tree is transformed by actions, you write reducers. Reducers are just pure functions that take the previous state and an action as parameters, and return the next state.


   **[⬆ Back to Top](#table-of-contents)**
    
155. ### Talk about Laravel Vapor Compatibility


     Instead of saying downsides we can say that there are few compromises of using Redux over Flux. Those are as follows:

     1. **You will need to learn to avoid mutations:** Flux is un-opinionated about mutating data, but Redux doesn't like mutations and many packages complementary to Redux assume you never mutate the state. You can enforce this with dev-only packages like `redux-immutable-state-invariant`, Immutable.js, or instructing your team to write non-mutating code.
     2. **You're going to have to carefully pick your packages:** While Flux explicitly doesn't try to solve problems such as undo/redo, persistence, or forms, Redux has extension points such as middleware and store enhancers, and it has spawned a rich ecosystem.
     3. **There is no nice Flow integration yet:** Flux currently lets you do very impressive static type checks which Redux doesn't support yet.


   **[⬆ Back to Top](#table-of-contents)**
    
156. ### What is Semantic Versioning?


     `mapStateToProps()` is a utility which helps your component get updated state (which is updated by some other components):

     ```javascript
     const mapStateToProps = (state) => {
       return {
         todos: getVisibleTodos(state.todos, state.visibilityFilter)
       }
     }
     ```

     `mapDispatchToProps()` is a utility which will help your component to fire an action event (dispatching action which may cause change of application state):

     ```javascript
     const mapDispatchToProps = (dispatch) => {
       return {
         onTodoClick: (id) => {
           dispatch(toggleTodo(id))
         }
       }
     }
     ```
     
     Recommend always using the “object shorthand” form for the `mapDispatchToProps`
        
     Redux wrap it in another function that looks like (…args) => dispatch(onTodoClick(…args)), and pass that wrapper function as a prop to your component.
      
      ```javascript
       const mapDispatchToProps = ({
         onTodoClick
       })
      ```


   **[⬆ Back to Top](#table-of-contents)**
    
157. ### What are Jobs and Middleware?


     Dispatching an action within a reducer is an **anti-pattern**. Your reducer should be *without side effects*, simply digesting the action payload and returning a new state object. Adding listeners and dispatching actions within the reducer can lead to chained actions and other side effects.


   **[⬆ Back to Top](#table-of-contents)**
    
158. ### Talk about Laravel User Interface (UI)

     You just need to export the store from the module where it created with `createStore()`. Also, it shouldn't pollute the global window object.

     ```javascript
     store = createStore(myReducer)

     export default store
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
159. ### Talk about Eloquent Subquery Enhancements?

     1. DOM manipulation is very expensive which causes applications to behave slow and inefficient.
     3. Due to circular dependencies, a complicated model was created around models and views.
     3. Lot of data changes happens for collaborative applications(like Google Docs).
     4. No way to do undo (travel back in time) easily without adding so much extra code.


   **[⬆ Back to Top](#table-of-contents)**
    
160. ### What are improved Authorization Responses?

     These libraries are very different for very different purposes, but there are some vague similarities.

     Redux is a tool for managing state throughout the application. It is usually used as an architecture for UIs. Think of it as an alternative to (half of) Angular. RxJS is a reactive programming library. It is usually used as a tool to accomplish asynchronous tasks in JavaScript. Think of it as an alternative to Promises. Redux uses the Reactive paradigm because the Store is reactive. The Store observes actions from a distance, and changes itself. RxJS also uses the Reactive paradigm, but instead of being an architecture, it gives you basic building blocks, Observables, to accomplish this pattern.


   **[⬆ Back to Top](#table-of-contents)**
    
161. ### What are lazy collections?


     You can dispatch an action in `componentDidMount()` method and in `render()` method you can verify the data.

     ```javascript
     class App extends Component {
       componentDidMount() {
         this.props.fetchData()
       }

       render() {
         return this.props.isLoaded
           ? <div>{'Loaded'}</div>
           : <div>{'Not Loaded'}</div>
       }
     }

     const mapStateToProps = (state) => ({
       isLoaded: state.isLoaded
     })

     const mapDispatchToProps = { fetchData }

     export default connect(mapStateToProps, mapDispatchToProps)(App)
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
162. ### How to make a constant and use globally?


     You need to follow two steps to use your store in your container:

     1. **Use `mapStateToProps()`:** It maps the state variables from your store to the props that you specify.
     2. **Connect the above props to your container:** The object returned by the `mapStateToProps` function is connected to the container. You can import `connect()` from `react-redux`.

         ```jsx harmony
         import React from 'react'
         import { connect } from 'react-redux'

         class App extends React.Component {
           render() {
             return <div>{this.props.containerData}</div>
           }
         }

         function mapStateToProps(state) {
           return { containerData: state.data }
         }

         export default connect(mapStateToProps)(App)
         ```


   **[⬆ Back to Top](#table-of-contents)**
    
163. ### How to remove /public from URL in laravel?


     You need to write a *root reducer* in your application which delegate handling the action to the reducer generated by `combineReducers()`.

     For example, let us take `rootReducer()` to return the initial state after `USER_LOGOUT` action. As we know, reducers are supposed to return the initial state when they are called with `undefined` as the first argument, no matter the action.

     ```javascript
     const appReducer = combineReducers({
       /* your app's top-level reducers */
     })

     const rootReducer = (state, action) => {
       if (action.type === 'USER_LOGOUT') {
         state = undefined
       }

       return appReducer(state, action)
     }
     ```

     In case of using `redux-persist`, you may also need to clean your storage. `redux-persist` keeps a copy of your state in a storage engine. First, you need to import the appropriate storage engine and then, to parse the state before setting it to undefined and clean each storage state key.

     ```javascript
     const appReducer = combineReducers({
       /* your app's top-level reducers */
     })

     const rootReducer = (state, action) => {
       if (action.type === 'USER_LOGOUT') {
         Object.keys(state).forEach(key => {
           storage.removeItem(`persist:${key}`)
         })

         state = undefined
       }

       return appReducer(state, action)
     }
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
164. ### What are the difference between soft delete & delete in Laravel?


     The **@** symbol is in fact a JavaScript expression used to signify decorators. *Decorators* make it possible to annotate and modify classes and properties at design time.

     Let's take an example setting up Redux without and with a decorator.

     * **Without decorator:**

         ```javascript
         import React from 'react'
         import * as actionCreators from './actionCreators'
         import { bindActionCreators } from 'redux'
         import { connect } from 'react-redux'

         function mapStateToProps(state) {
           return { todos: state.todos }
         }

         function mapDispatchToProps(dispatch) {
           return { actions: bindActionCreators(actionCreators, dispatch) }
         }

         class MyApp extends React.Component {
           // ...define your main app here
         }

         export default connect(mapStateToProps, mapDispatchToProps)(MyApp)
         ```

     * **With decorator:**

         ```javascript
         import React from 'react'
         import * as actionCreators from './actionCreators'
         import { bindActionCreators } from 'redux'
         import { connect } from 'react-redux'

         function mapStateToProps(state) {
           return { todos: state.todos }
         }

         function mapDispatchToProps(dispatch) {
           return { actions: bindActionCreators(actionCreators, dispatch) }
         }

         @connect(mapStateToProps, mapDispatchToProps)
         export default class MyApp extends React.Component {
           // ...define your main app here
         }
         ```

     The above examples are almost similar except the usage of decorator. The decorator syntax isn't built into any JavaScript runtimes yet, and is still experimental and subject to change. You can use babel for the decorators support.


   **[⬆ Back to Top](#table-of-contents)**
    
165. ### How we can upload files in laravel?

     You can use **Context** in your application directly and is going to be great for passing down data to deeply nested components which what it was designed for. Whereas **Redux** is much more powerful and provides a large number of features that the Context API doesn't provide. Also, React Redux uses context internally but it doesn't expose this fact in the public API.


   **[⬆ Back to Top](#table-of-contents)**
    
166. ### Why are Redux state functions c166. ### How to create real time sitemap.xml file in Laravel?


     Reducers always return the accumulation of the state (based on all previous and current actions). Therefore, they act as a reducer of state. Each time a Redux reducer is called, the state and action are passed as parameters. This state is then reduced (or accumulated) based on the action, and then the next state is returned. You could *reduce* a collection of actions and an initial state (of the store) on which to perform these actions to get the resulting final state.


   **[⬆ Back to Top](#table-of-contents)**
    
167. ### How to use skip() and take() in Laravel Query?


     You can use `redux-thunk` middleware which allows you to define async actions.

     Let's take an example of fetching specific account as an AJAX call using *fetch API*:

     ```javascript
     export function fetchAccount(id) {
       return dispatch => {
         dispatch(setLoadingAccountState()) // Show a loading spinner
         fetch(`/account/${id}`, (response) => {
           dispatch(doneFetchingAccount()) // Hide loading spinner
           if (response.status === 200) {
             dispatch(setAccount(response.json)) // Use a normal function to set the received state
           } else {
             dispatch(someError)
           }
         })
       }
     }

     function setAccount(data) {
      return { type: 'SET_Account', data: data }
     }
     ```


   **[⬆ Back to Top](#table-of-contents)**
    
168. ### What is tinker in laravel?

Tinker is command line code functionality where you can write Laravel code in CLI.

   **[⬆ Back to Top](#table-of-contents)**
    
169. ### What is a REPL?

...


   **[⬆ Back to Top](#table-of-contents)**
    
170. ### How to use multiple 'OR' condition in Laravel Query?
...

   **[⬆ Back to Top](#table-of-contents)**
    
171. ### Please write some additional where Clauses in Laravel?
    
...

   **[⬆ Back to Top](#table-of-contents)**
    
172. ### How to check column is exists or not in a table using Laravel?

...

   **[⬆ Back to Top](#table-of-contents)**
    
173. ### What is eager loading in Laravel?
   
...

   **[⬆ Back to Top](#table-of-contents)**
    
174. ### How to generate application key in laravel?


  ...


   **[⬆ Back to Top](#table-of-contents)**
    
175. ### What is LTS version of Laravel?


    LTS version is a version where the support is longer i.e it gets longer fixes and support and is a stable version.


   **[⬆ Back to Top](#table-of-contents)**
    
176. ### How to use GROUP_CONCAT() with JOIN in Laravel?

...


   **[⬆ Back to Top](#table-of-contents)**
    
177. ### How to extend login expire time in Auth?

...

   **[⬆ Back to Top](#table-of-contents)**
    
178. ### How to extend a layout file in laravel view?

...

   **[⬆ Back to Top](#table-of-contents)**
    
179. ### How do you use yield()?

...

   **[⬆ Back to Top](#table-of-contents)**
    
182. ### What is ACL in laravel?

...


   **[⬆ Back to Top](#table-of-contents)**
    
183. ### How to check Ajax request in Laravel?

...


   **[⬆ Back to Top](#table-of-contents)**
    
184. ### How to check if value is sent in request?

...


   **[⬆ Back to Top](#table-of-contents)**
    
185. ### Laravel String Helper functions?

...

   **[⬆ Back to Top](#table-of-contents)**
    
186. ### Laravel Array Helper functions?

...


   **[⬆ Back to Top](#table-of-contents)**
    
187. ### How to exclude a route with parameters from CSRF verification?

...


   **[⬆ Back to Top](#table-of-contents)**
    
188. ### What are policies classes?

...

   **[⬆ Back to Top](#table-of-contents)**
    
189. ### How to rollback last migration?


...

   **[⬆ Back to Top](#table-of-contents)**
    
190. ### What do you mean by Laravel Dusk?

...


   **[⬆ Back to Top](#table-of-contents)**
    
191. ### Explain Laravel echo

Used with broadcasting and sockets.


   **[⬆ Back to Top](#table-of-contents)**
    
192. ### What is namespace in Laravel?

...


   **[⬆ Back to Top](#table-of-contents)**
    
193. ### What is Laravel Forge?

...

   **[⬆ Back to Top](#table-of-contents)**
    
194. ### State the difference between CodeIgniter and Laravel.

...

   **[⬆ Back to Top](#table-of-contents)**
    
195. ### What is an Observer?

...

   **[⬆ Back to Top](#table-of-contents)**
    
196. ### What is the use of the bootstrap directory?

...


   **[⬆ Back to Top](#table-of-contents)**
    
197. ### What is the default session timeout duration?


...

   **[⬆ Back to Top](#table-of-contents)**
    
198	Explain API.PHP route

...


   **[⬆ Back to Top](#table-of-contents)**
    
199. ### Define hashing in Laravel

...

   **[⬆ Back to Top](#table-of-contents)**
    
200. ### What is Localization?
...

   **[⬆ Back to Top](#table-of-contents)**
    
202. ### How to share data with views?

...

   **[⬆ Back to Top](#table-of-contents)**
    
203	How to generate a request in Laravel?


...


   **[⬆ Back to Top](#table-of-contents)**
    
204. ### I just have installed a fresh version of Laravel 5, and I have the white screen of death. What’s wrong?


..

   **[⬆ Back to Top](#table-of-contents)**
    
205. ### How to assign a variable value for all view file?

...

   **[⬆ Back to Top](#table-of-contents)**
    
206. ### How to make a constant and use globally?

..

207. ### How to check current installed version of Laravel?

...

   **[⬆ Back to Top](#table-of-contents)**
    
208. ### What does "composer dump-autoload" do?

..


   **[⬆ Back to Top](#table-of-contents)**
    
209. ### What is Kept in vendor directory of Laravel?

   ...

   **[⬆ Back to Top](#table-of-contents)**
    
210. ### What does PHP compact function do?alled reducers?

   ...
211. ### What does PHP compact function do?alled reducers?
    `APP_KEY` is used for encryption of cookies.

   **[⬆ Back to Top](#table-of-contents)**
