# Work in progress rules
ADD_GUILE_MODULE(FILES
	implication-direct-evaluation.scm
	instantiation.scm
	implication-instantiation.scm
	and-introduction.scm
	and-lambda-factorization-double-implication.scm
	and-simplification.scm
	equivalence-scope-distribution.scm
	equivalence-to-implication.scm
	implication-and-lambda-factorization.scm
	implication-implicant-conjunction.scm
	implication-implicant-disjunction.scm
	implication-implicant-distribution.scm
	implication-scope-to-implication.scm
	implication-to-implication-scope.scm
	inversion.scm
	closed-lambda-introduction.scm
	closed-lambda-evaluation.scm
	predicate-lambda-evaluation.scm
	and-lambda-distribution.scm
	and-to-context.scm
	contextualize.scm
	extensional-similarity-evaluation.scm
	intensional-inheritance-evaluation.scm
	member-to-evaluation.scm
	or-simplification.scm
	abduction.scm
	and-as-1st-arg-inside-inheritance-link.scm
	and-as-2nd-arg-inside-inheritance-link.scm
	and-breakdown.scm
	and-elimination.scm
	compile-rules.scm
	decontextualize.scm
	evaluation-to-member.scm
	forall-implication-to-higher-order.scm
	forall-instantiation.scm
	implication-and.scm
	induction.scm
	inheritance-to-member.scm
	intensional-similarity-evaluation.scm
	member-to-inheritance.scm
	not-introduction.scm
	not-elimination.scm
	not-simplification.scm
	ontological-inheritance.scm
	or-breakdown.scm
	or-introduction.scm
	or-elimination.scm
	or-evaluation.scm
	precise-modus-ponens.scm
	README.md
	subset-evaluation.scm
	symmetric-modus-ponens.scm
	term-probability.scm
	transitive-similarity.scm
	and-evaluation.scm
	and-to-subset-rule1.scm
	and-to-subset-rulen.scm
	and-transformation.scm
	attraction.scm
	context-free-to-sensitive.scm
	evaluation-implication.scm
	implication-introduction.scm
	inheritance.scm
	negated-subset-evaluation.scm
	or-transformation.scm
	similarity.scm
	negation-introduction.scm
	temp-deduction.scm
	formulas.scm
	MODULE_DESTINATION "${GUILE_SITE_DIR}/opencog/pln/rules/wip"
)
