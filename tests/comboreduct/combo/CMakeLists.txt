ADD_CXXTEST(vertexUTest)
TARGET_LINK_LIBRARIES(vertexUTest
	comboreduct
	comboant
	cogutil
)

ADD_CXXTEST(messageUTest)
TARGET_LINK_LIBRARIES(messageUTest
	comboreduct
	comboant
	cogutil
)

ADD_CXXTEST(listUTest)
TARGET_LINK_LIBRARIES(listUTest
	comboreduct
	comboant
	cogutil
)

ADD_CXXTEST(similarityUTest)
TARGET_LINK_LIBRARIES(similarityUTest
	comboreduct
	comboant
	cogutil
)

ADD_CXXTEST(annUTest)
TARGET_LINK_LIBRARIES(annUTest
	comboreduct
	cogutil
)

ADD_CXXTEST(procedure_callUTest)
TARGET_LINK_LIBRARIES(procedure_callUTest
	comboreduct
	comboant
	cogutil
)

ADD_CXXTEST(procedure_repositoryUTest)
TARGET_LINK_LIBRARIES(procedure_repositoryUTest
	comboreduct
	comboant
	cogutil
)

ADD_CXXTEST(interpreterUTest)
TARGET_LINK_LIBRARIES(interpreterUTest
	comboreduct
	comboant
	cogutil
)

ADD_CXXTEST(iostream_comboUTest)
TARGET_LINK_LIBRARIES(iostream_comboUTest
	comboreduct
	comboant
	cogutil
)
