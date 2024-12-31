add_executable(Postie
    main.cpp
    mainwindow.cpp
    mainwindow.h
)

target_link_libraries(Postie PRIVATE
    Qt6::Core
    Qt6::Widgets
)