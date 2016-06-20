# nrser.meteor_react_component role #

a role i'm using to generate React components for my meteor projects.

it reflects my personal evolving structure and is not at this time intended for external use.

## use ##

components are put in `<meteor-app-dir>/imports/ui` in either

-   `/imports/ui/pages`
    -   if they're 'pages' that load as the entire view (except some persisitent nav or whatever)
-   `/imports/layouts`
    - if they're used as page layouts
-   `/imports/components`
    -   everything else


examples:

want to generate 

    qb comp --page 
