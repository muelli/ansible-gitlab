Changelog
=========

v0.1.0
------

*Unreleased*

- Add Changelog. [drybjed]

- Add support for GitLab 7.10.

  Template of ``gitlab.yml`` configuration file is updated to GitLab 7.10.

  Variable ``gitlab_email_name`` is renamed to ``gitlab_email_display_name``.

  Removed ``gitlab_email_support``, ``gitlab_signup_enabled`` and
  ``gitlab_default_projects_limit`` variables.

  Added ``gitlab_email_reply_to`` variable.

  Install ``libkrb5-dev`` package before GitLab CE installation (required on
  Debian Jessie). [drybjed]

