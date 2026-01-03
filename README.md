# Drupal Recipe - Base Setup

This recipe bootstraps a Drupal site by:

- Ensuring required core modules are enabled
- Downloading and enabling a set of contrib modules
- Applying basic site configuration

## Add repository

```
ddev composer config repo.base_setup vcs https://github.com/pachabhaiya/drupal-base-setup.git
```

## Require recipe

```
ddev composer require pachabhaiya/base_setup:dev-master
```

## Apply recipe

```
ddev drush recipe ../recipes/base_setup
```
