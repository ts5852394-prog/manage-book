# manage-book
new repository
#include <iostream>
#include <vector>
#include <string>

// Define Book, Borrower, Transaction classes as described above

class LibrarySystem {
public:
    std::vector<Book> books;
    std::vector<Borrower> borrowers;
    std::vector<Transaction> transactions;

    void addBook(const Book& book) {
        books.push_back(book);
    }

    void issueBook(const std::string& bookID, const std::string& borrowerID) {
        // Find book and borrower, create transaction, update book status
    }

    void returnBook(const std::string& transactionID) {
        // Find transaction, update return date, update book status
    }

    // Other methods for viewing, searching, updating, etc.
};

int main() {
    LibrarySystem myLibrary;
    // Implement menu and call LibrarySystem methods
    return 0;
}
