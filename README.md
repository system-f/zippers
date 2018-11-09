Zippers
=======

The term zipper is a colloquial used to describe n-hole (most often, 1-hole) contexts. That is, a data structure that has a _hole_ or _pointer_ focused on a specific element with the ability to efficiently traverse to its neighbouring elements, providing an elegant solution for the need to efficiently traverse and _modify_ immutable data structures.

In this talk, we will look at examples of zippers for canonical data structures such as lists and other products and sums. We will then define comonads and see the relationship between zippers and comonads.

Most of this talk will be spent on the practical application of zippers in everyday programming. We will solve some simple problems using zippers. We will then contrast why we might use a zipper, compared to a lens.

Finally, for a fun and interesting observation, we will look at the algebraic structure of products and sums, then compute the derivative of these structures. Turns out, a derivative of a data structure is its zipper ("McBride, Conor, et al (2005). ∂ for Data: Differentiating Data Structures").