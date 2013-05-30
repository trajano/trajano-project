Trajano project
===============

This is a set of projects that define different project properties at an 
organisation level.   Having a common set of project properties will ensure
better compatibility between services and applications used throughout the
organisation.

This project contains archetype modules used to jump-start development and
project type specific POMs that define version levels of artifacts to ensure
consistency within the organisation.

At this level, version properties such as `checkstyle-plugin.version` are
defined in `properties` that are inherited by the different project types.
Versions that may change depending on project type due to JDK level requirements
are defined in the project type POMs.
