Local Code Style Guide
======================

There's no single right way to code. However, if you're coding in a shared environment then it
can be helpful to have an agreed way of doing things. The following list is an attempt at providing 
a local style guide for shared code in the Orengo Bioinformatics group at UCL

The original list was taken [from a comment on a discussion about code review](http://www.perlmonks.org/?node_id=989115) and seems a pretty good place to start. This is intended to be an evolving, working document: everyone should feel free to suggest additions, modifications, deletions or simply request clarifications (in the form of pull requests or raising issues on github).


1. Correctness, simplicity and clarity come first.
1. Avoid unnecessary cleverness. If you must rely on cleverness, encapsulate and comment it.
1. Avoid duplication (DRY).
1. Coupling and Cohesion. Systems should be designed as a set of cohesive modules as loosely coupled as is reasonably feasible.
1. Data hiding. Minimize the exposure of implementation details.
1. Minimize the scope of variables, pragmas, etc..
1. Establish a rational error handling policy and follow it strictly.
1. Interfaces matter. Once an interface becomes widely used, changing it becomes practically impossible (just about anything else can be fixed in a later release). Design the module's interface first.
1. Design interfaces that are: consistent; easy to use correctly; hard to use incorrectly; easy to read, maintain and extend; clearly documented; appropriate to your audience. Be sufficient, not complete; it is easier to add a new feature than to remove a mis-feature.
1. Write components that are testable in isolation.
1. The result of every file operation or API call or external command should be checked, and unexpected results handled.
1. Use descriptive, explanatory, consistent and regular names.
1. Avoid magic numbers.
1. Don't optimize prematurely. Benchmark before you optimize. Comment why you are optimizing.
1. Agree upon a coherent layout style and automate it.
1. Adopt a policy of zero tolerance for warnings and errors. Tools such as Perl::Tidy and Perl::Critic can help here.
1. Commenting: prefer to make the code obvious; don't belabor the obvious; comments describe what and why not how.
1.  Separate user vs maintainer documentation.
1.  Use a revision control system and single-step automated build/test.
1.  "Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live" (Damian Conway)
